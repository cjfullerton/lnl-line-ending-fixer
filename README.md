Simple script for fixing line endings that was written to deal with a specific repeat issue with line endings being mangled on transfer to a remote HPC system.

1. Place the two files in the data folder
2. Run `chmod u+rwx fix_line_endings.sh` and execute the script using `./fix_line_endings.sh`.
3. The bash script executes the vim script on all files `*.sh` and `fitfile.txt` in subfolders, forcing UNIX line endings and ensuring the model works.
