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

## LOG MANAGEMENT

------------------------

- syslog - Syslog is a vague concept, generally referring to the following 3 things:


 Syslog Daemon: It is a daemon that listens for logs and writes them to a specific location. The location(s) is defined in the configuration file for the daemon. rsyslog is the Syslog daemon shipped with most of the distros. 
    
 Syslog Message Format: It refers to the syntax of Syslog messages. The syntax is usually defined by a standard (for eg RFC5424).
 
 Syslog Protocol: It refers to the protocol used for remote logging. Modern Syslog daemons can use TCP and TLS in addition to UDP which is the legacy protocol for remote logging.
 
 ex- sudo ls /var/log
 
 alternatives.log ,bootstrap.logs
 
 - journalctl - used to view systemd, kernel and journal logs.
 
 1. To display all logs
 
   $ journalctl
   
 2. To reverse the order or to display the new entries first.
 
     $journalctl -r
     
 3. To display only a few log entries
 
   $journalctl -n 2
   
 4. To display the boots of the system.
 
  $journalctl --list-boots
  
- custom logs - logs that contain diagnostic information from custom applications, other cloud providers, or an on-premise environment.

 Default Log File Location
 
   ls -l /var/log.
   
   
 ## Network Management
 
 ------------------------
 
 * ifcongif - used to dispaly the system network interface information
    
* hostname - used to display machine hostname

* netstat -l - used to display all listening ports

* netstat -t -used to dispaly all TCP connections

* http & https - HTTPS uses TLS (SSL) to encrypt normal HTTP requests and responses, and to digitally sign those requests and responses, HTTP Works at the Application Layer and HTTPS works at Transport Layer.

* internal network - A network where the establishment, maintenance, and provisioning of security controls are under the direct control of organizational 

ex - employees or contractors.


* external network - A network not controlled by the organization.

ex- firewalls, load balancers, web servers, ftp servers, 

- TCP - it is a communications standard that enables application programs and computing devices to exchange messages over a network. 

ex- 

    Web
    
    SSH, FTP, telnet
    
    SMTP, sending mail
    
    IMAP/POP, receiving mail
    
- UDP - it s a communications protocol that is primarily used to establish low-latency and loss-tolerating connections between applications on the internet

ex-
    Voice over IP (VoIP), online games, and media streaming
    
- private subnet - private subnet are back-end servers that don't need to accept incoming traffic from the internet and therefore do not have public IP addresses; 


- public subnet - A public subnet is a subnet that's associated with a route table that has a route to an internet gateway.

- CDIR (Classless Inter-Domain Routing or supernetting) - it s a group of IP addresses that are allocated to the customer when they demand a fixed number of IP addresses.


    To calculate the CIDR prefix for a given IP address range, you need to count the number of leading 1 bits in the binary representation of the subnet mask. For example, the subnet mask of    255.255. 255.0 (in dotted decimal notation) has 24 leading 1 bits, so its CIDR prefix is /24 .23-Feb-2023.
    
    
 - port range - Port numbers 0 - 1023 are used for well-known ports
 
                Port numbers 1024 - 65535 are available for the following user applications
                
                Port numbers 1024 - 49151 are reserved for user server applications.
                
                Port numbers 49152 - 65535 are reserved for clients
                
    






 
 
 
 
 


       
-        
       
 



















































