# Shell-scripting
Shell scripting guide
### step1 Create a folder
```bash
mkdir shell-scripting
```
![folder](images/folder.png)

### step2 create and use vim to edit
```bash
vim my_first_shell_script.sh
```
![Screenshot vim editor](images/vimshell.png)

### step2 input following command 
```
#!/bin/bash

# Create directories
mkdir Folder1
mkdir Folder2
mkdir Folder3

# Create users
sudo useradd user1
sudo useradd user2
sudo useradd user3
```
![Screenshot script](images/editshell.png)

press ESC key followed by :wq and press enter to save and exit.
![saved](images/exitsave.png)
 ### step3 The script is inside the  Shell-scripting folder
Use this commanand to check the file is created and the owner permission.
```bash
ls  -latr
```
![check](images/ls-latr.png)
Output
![review permission](images/outputlatr.png)
### execute the sript
```bash
./my_first_shell_script.sh
```
![execute shell sript](images/execshell.png)
If you get 'permission denied'
### Use this command to add  execute permission to the owner;
```
chmod 700 my_first_script.sh
```
![elevate permission](images/chmodshell.png)

Run 
```bash
ls -latr
```
you will see that  the owner permission has been elevated to be able to execute the script.
![confirm bash executor](images/permsucc.png)

### Now execute this script again, you should see successful.

![password](images/enterpassword.png)
enter user password


### To confirm if the files and users were created from our script;
for created folders
Run
```bash
ls
```
![check folder](images/foldersuccess.png)


For created Users
Run:
```bash
id user1 user2 user3
```
![confirm created users](images/usersuccess.png)
For bash

### For sh
### Use vim to open the editor press i to enter insert mode paste this command
```bash
#!/bin/sh

# Create directories
mkdir Folder4
mkdir Folder5
mkdir Folder6

# Create users
sudo useradd user4
sudo useradd user5
sudo useradd user6
```
![sh example](images/pressi-insert-edit.png)

save and exit
### Execute the file again and verify with ls and id user4 to verify the execution. Using thesame process from the first step.
![confirm for sh](images/shsuccess.png)

### How to use variable to retieve value
Run;
```bash
name="John"
```
```bash
echo $name
```
to explore more
```bash
echo My name is $name
```
![screenshot variable input](images/varinput.png)
![screenshot variable output](images/varoutpu.png)

LICENSE
This project is opensource, your suggestions and comments are welcome!
