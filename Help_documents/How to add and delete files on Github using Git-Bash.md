To add a file to Github after you have saved the file in the corresponding folder locally:

1. goto the folder which contains the file, in Git-Bash

2. type the following: git add <filename.suffix>
3. then type: git commit -m "enter commit message here"
4. then type: git push

The file is now in the corresponding folder on Github. Success :)

To delete all files from a Github folder, first cd to the folder you want to delete a file from, then:

1. type the following: git add . -A
2. then type: git commit -m "enter commit message here"
3. then type: git push

The files will no longer be shown on Github. Success :)