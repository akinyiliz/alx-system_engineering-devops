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

