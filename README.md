# Recycle & Restore Unix Shell Scripts

## Phase 1 - Recycle Script
* Script called recycle that mimics the rm command. Accepts the name of file as command line argument just as `rm` does, but insteadk, the script moves it to a recyclebin directory called recyclebin located in the home directory.

* Usage: `bash recycle filename`

## Phase 2 - Restore Script
* Script called restore that restores individual files back to their original location. User determines which file to restore and uses the file name followed by the inode number to restore file

* Usage: `bash restore filename_1234`

## Phase 3 - Multiple files, Wildcards, and Options Flags
* Script ensures that command can remove multiple files at a time, and be able to implement wildcards. Also enables interactive and verbose functionality to scripts.

* Usage: `bash recycle -iv file1 file2 file3`

## Phase 4 - Recycle Files Recursively
* Command removes directories and their contents recursively using the -r option

## Phase 5 - Restore Files Recycled Recursively
* Script has added functionality that enables the restoration of files that were recycled recursively. 

