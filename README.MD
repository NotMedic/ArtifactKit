# There is no licensed Cobalt Strike property within this repository. 
# This is only the necessary Visual Studio configuration files
# There is no support provided. Issues will be ignored, Pull requests will be reviewed and merged. 

## To Build:

Copy the contents of src-common and src-main from your authorized copy of Cobalt Strike into the src-common and src-main directories. 

You'll need to modify patch.c to read `(char *)buffer` instead of `buffer`.  VS will tell you which lines are broken when you try to comile. :)



In Visual Studio, go to __Build -> Batch Build and click "Select All."__ There should be 20 in total.

You should see `========== Build: 20 succeeded, 0 failed, 0 up-to-date, 0 skipped ==========`


You'll find the compiled output in the "output" directory.

Copy your "artifact.cna" into that directory
