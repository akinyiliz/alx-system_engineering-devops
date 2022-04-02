__Shell Basics__

0. script that prints the absolute path name of the current working directory .
  
   _#!/bin/bash_
   
   _pwd_
   
1. script that dsplays the contents list of your current directory.

   _#!/bin/bash_
   
   _ls_
   
2. script that changes the working directory to the user’s home directory.

   _#!/bin/bash_
   
   _cd_

3. script that display current directory contents in a long format.

   _#!/bin/bash_
   
   _ls -l_

4. Display current directory contents, including hidden files (starting with .). Use the long format. 

   _#!/bin/bash_
   
   _ls -a -l_

5. Display current directory contents: Long format, with user and group IDs displayed numerically, and hidden files (starting with .)	
	
   _#!/bin/bash_
   
   _ls -al -l -a_

6.script that creates a directory named my_first_directory in the /tmp/ directory.y

   _#!/bin/bash_
   
   _mkdir  /tmp/my_first_directory_

7. Move the file betty from /tmp/ to /tmp/my_first_directory.		
   _#!/bin/bash_
   
   _mv /tmp/betty /tmp/my_first_directory_

8. Delete the file betty	.
	
   _#!/bin/bash_
   
   _rm  /tmp/my_first_directory/betty_

9. Delete the file betty.
		
   _#!/bin/bash_
   
   _rmdir /tmp/my_first_directory_
  	
1. script that changes the working directory to the previous one.	

  _#!/bin/bash_
  
   _cd  -_

11.  script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
    
    _#!/bin/bash_
    
    _ls -la . .. /boot_

12.  script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

    _#!/bin/bash_
    
    _file /tmp/iamafile_

13. Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

    _#!/bin/bash_
    
    _ln -s /bin/ls  _ls_ _

14. Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

    _#!/bin/bash_
    
    _cp -u ./*.html  ../_
