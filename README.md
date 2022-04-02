0. script that switches the current user to the user betty
#!/bin/bash
su betty

1.script that prints the effective username of the current user.
 #!/bin/bash
whoami

2. script that prints all the groups the current user is part of
#!/bin/bash
groups

3. script that changes the owner of the file hello to the user betty.
#!/bin/bash
chown betty hello

4.script that creates an empty file called hello
 #!/bin/bash
touch hello

5. script that adds execute permission to the owner of the file hello
 #!/bin/bash
chmod u+x hello

6.   script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
#!/bin/bash
chmod ug+x,o+r hello

7. script that adds execution permission to the owner, the group owner and the other users, to the file hello
#!/bin/bash
chmod a+x hello

8. #!/bin/bash
chmod 007 hello

9. #!/bin/bash
chmod 753 hello

10. #!/bin/bash
chmod --reference=olleh hello

11. #!/bin/bash
chmod a+X *

12. script that creates a directory called my_dir with permissions 751 in the working directory
#!/bin/bash
mkdir -m 751 my_dir

13. #!/bin/bash
chgrp school hello

14. #!/bin/bash
chown vincent:staff *

15. #!/bin/bash
chown -h vincent:staff _hello

16. #!/bin/bash
chown --from=guillaume betty hello

17. script that will play the StarWars IV episode in the termina
#!/bin/bash
telnet towel.blinkenlights.n
