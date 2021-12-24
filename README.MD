# To Build:

Copy the contents of src-common and src-main from your authorized copy of Cobalt Strike into the src-common and src-main directories. 

You'll need to modify patch.c to read `(char *)buffer` instead of `buffer`.  VS will tell you which lines are broken when you try to comile. :)



In Visual Studio, go to __Build -> Batch Build and click "Select All."__ There should be 20 in total.
You'll find the compiled output in the "output" directory.
Copy your "artifact.cna" into that directory
 

There is no support provided. Issues will be ignored, Pull requests will be reviewed and merged. 
