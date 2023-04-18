# LINUX DOCUMENTS

===============

 ## FILE MANAGEMENT
 
---------------

- LS - List of file and directories.
ex- ls
     Desktop , download , pictures , file
     
 - ls -l - Listing files and directories in long list format.
 ex- ls -l <directory name>
      
 - touch - Create the file

eg- touch demo (filename)

- cat- Display file contents

 eg- cat demo
 
- CP - copying the file

eg- cp file1 file2

- MV - Moving the file

eg- mv demo demo1

- RM - Removing the file

eg - rm demo.

- MKDIR - Makeing directory

eg - mkdir demofirst

- rm - deleting the file

eg- rm demo1

- rmdir - Removing the directory

eg - rmdir demofirst

- pwd - print working directory

- cd - to change directory

- More - command lines display contents in paper formats

- Tail - display last parts of file
 
- df- display the amount of free space available in the system.

- du - disk usage

- grep - search for matching pattern

ex- grep “employee” testfile1

- cp -r - To copy a file in a different directory

ex- cp -r <sourceDirectory> <destinationDirectory>  

- grep -i - Search for files

ex- ls –l | grep –i test

- wc -l - prints only the length of the longest in a file.

ex- wc -l filename.

- tar-  Making an uncompressed tar archive with -cvf option

ex- tar cvf file.tar *.txt  

- zip- Allows you to compress multiple files into a single compressed archive file

ex- zip myfile.zip filename.txt

- unzip- Extract ZIP file

ex- unzip filename.zip

# VI EDITOR

-I- Insert the cursor
- ESC - terminate the insert mode
- :w - quit without saving
- :wq - save the file and quit
- /word - search the word in vi
- :%s/oldword/newword/g) -  replace a word with new word in vi

## User Management 

--------------------

- SSH - To Access a Remote Server

ex- ssh 192.168.56.101

- scp - Copy a File from Local to Remote Server

ex- scp Desktop/sample_example.txt root@136.183.142.28:/home/remote_dir

- sudo - to give permission to the user

ex- sudo apt update

- su -switch the current user to any other user

ex- su username.

- chmod - used to change the access mode of a file.

ex- chmod <Operations> <File/Directory Name>

- chown - Change the Owner of a File

ex- chown user FILE(s)

## Configuration Management

--------------------------------

- env- env - used to display your current environment or run a specified command in a changed environment

  ex : env
  
  - echo $ PATH - used to display the path of the url
  
- export - used to mark variables and functions to be passed to child process
  
  ex : export
  
 - hostname - displays the name of the current host system
 
 ex- hostname 
 
 - netstat - To display connection information.
 
 ex- netstat
 
 - crontab -l - View Root User Cronjob on Linux

- kill- used to send a signal to a process, which can be used to kill the process

- pkill- used to send signals to processes.

- wget- To download a web file from internet

ex- wget url.

- ping - To check connectivity between the nodes.

ex- ping google.com

- uname -a - show kernel config 

- diff - show difference between files

- ps - used to display the current running process
  ex : ps 
       PID TTY  TIME CMD
       
- ps -e - used to display daemons
  ex : ps -e
       PID TTY TIME CMD 
       
- history - to display all used commands

ex- history


       
-        
       
 



















































