__Shell Basics__

0. script that prints the absolute path name of the current working directory .
  
   _#!/bin/bash
   pwd_
   
1. script that dsplays the contents list of your current directory.

   _#!/bin/bash
   ls_
   
2. script that changes the working directory to the user’s home directory.

   _#!/bin/bash
   cd_

3. script that display current directory contents in a long format.

   _#!/bin/bash	
   ls -l_

4. Display current directory contents, including hidden files (starting with .). Use the long format. 

   _#!/bin/bash
   ls -a -l_

5. Display current directory contents: Long format, with user and group IDs displayed numerically, and hidden files (starting with .)	
	
   _#!/bin/bash
   ls -al -l -a_

6.script that creates a directory named my_first_directory in the /tmp/ directory.y

   _#!/bin/bash
   mkdir  /tmp/my_first_directory_

7. Move the file betty from /tmp/ to /tmp/my_first_directory.		
   _#!/bin/bash
   mv /tmp/betty /tmp/my_first_directory_

8. Delete the file betty	.
	
   _#!/bin/bash
   rm  /tmp/my_first_directory/betty_

9. Delete the file betty.
		
   _#!/bin/bash
   rmdir /tmp/my_first_directory_
  	
1. script that changes the working directory to the previous one.	

  _#!/bin/bash	
   cd  -_

11.  script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.	

    _#!/bin/bash
    ls -la . .. /boot_

12.  script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

    _#!/bin/bash
    file /tmp/iamafile_

13. Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

    _#!/bin/bash		
    ln -s /bin/ls  _ls_ _

14. Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

    _#!/bin/bash+		
    cp -u ./*.html  ../_


__Shell Permissions__

0. Script that switches the current user to the user betty.

_#!/bin/bash_

_su betty_

1.script that prints the effective username of the current user.

_#!/bin/bash_

_whoami_

2. script that prints all the groups the current user is part of.

_#!/bin/bash_

_groups_

3. script that changes the owner of the file hello to the user betty.

_#!/bin/bash_

_chown betty hello_

4.script that creates an empty file called hello.

 _#!/bin/bash_
 
_touch hello_

5. script that adds execute permission to the owner of the file hello.

 _#!/bin/bash_
 
_chmod u+x hello_

6.   script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

_#!/bin/bash_

_chmod ug+x,o+r hello_

7. script that adds execution permission to the owner, the group owner and the other users, to the file hello.

_#!/bin/bash_

_chmod a+x hello_

8. _#!/bin/bash_

_chmod 007 hello_

9. _#!/bin/bash_

_chmod 753 hello_

10. _#!/bin/bash_

_chmod --reference=olleh hello_

11. _#!/bin/bash_

_chmod a+X *_

12. script that creates a directory called my_dir with permissions 751 in the working directory.

_#!/bin/bash_

_mkdir -m 751 my_dir_

13. _#!/bin/bash_

_chgrp school hello_

14. _#!/bin/bash_

_chown vincent:staff *_

15. _#!/bin/bash_

_chown -h vincent:staff _hello_

16. _#!/bin/bash_

_chown --from=guillaume betty hello_

17. script that will play the StarWars IV episode in the terminal.

_#!/bin/bash_

_telnet towel.blinkenlights.n_



