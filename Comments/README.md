How to comment in Bash scripts
### step1 create a new script or use an existing script vim text editor to edit the desired script
Follow the following steps
Run
```bash
vim comment.ch
```
  ![folder](Shell-scripting/Comments/comment.png)

### Press i to enter edit mode and write comment starting with '#'
```
#!/bin/bash
# This is a single-line comment in Bash
echo "Hello, you are learning Bash Scripting on DAREY.IO!" # This is also a comment, following a command
```

  ![folder](Shell-scripting/Comments/one-line.png)

### press esc and :wq to save and exit
### Execute the Bash file 

  ![folder](Shell-scripting/Comments/run.png)
### Give execustion permission to the owner
Run
```bash
chmod 741 comment.sh
```
### Execute the file again

  ![folder](Shell-scripting/Comments/running.png)

### For multi-line Comment use '#' before comment on each and within line of comment. 
Below
### use vim to open and i to enter the insert mode again
paste;
```
# This is another way to create
# a multi-line comment. Each line
# is prefixed with a # symbol.
echo "Here is an actual code that gets executed"
```
  ![For multi-line comments](Shell-scripting/Comments/multiline.png)
Press esc to exit insert mode and :wq to save and exit
###  Execute the file again

  ![folder](Shell-scripting/Comments/multirunning.png)
### To see all content in the file using cat;
Run
```bash
cat comment.sh
```

  ![folder](Shell-scripting/Comments/catsh.png)

LICENCE
This project is opensource for education purposes, and is open to contributions and Shell-scripting/Comments/advice

![folder](Shell-scripting/Comments/foldersuccess.png)
