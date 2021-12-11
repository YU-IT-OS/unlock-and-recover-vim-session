# Unlock and Recover Vim Session

Upload `final.sh` to github, remember that `final.sh` must print a usage summery if it is not run with the appropriate number of arguments.

Do not upload your script until it is 100% complete and passes all of your personal tests.  This is a verification environment, not a testing environment, if you have questions, please let me know!


## Specifications
"Unlock and recover vim session" script. Those of you who have been disconnected from a vim session probably know that when you try to get back in you are taken through a tedious process of recovery and deleting a swap file. This script should save off the original version of the file to filename.orig in the same directory where filename is the name of the original file, programmatically recover the file from the swap file and remove the swap file. It should then output an sdiff between the files. This script should take the full path of the file as an argument. I recommend using cp,vim -r help.txt (where help.txt is the name of the file you want to recover), and sdiff. 
