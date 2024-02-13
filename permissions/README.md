PERMISSIONS, HOLBERTON CODING SCHOOL:

What do the commands chmod, sudo, su, chown, chgrp do.
Linux file permissions.
How to represent each of the three sets of permissions (owner, group, and other) as a single digit.
How to change permissions, owner and group of a file.
Why can’t a normal user chown a file.
How to run a command with root privileges.
How to change user ID or become superuser.

rwx rwx rwx = 111 111 111
rw- rw- rw- = 110 110 110
rwx --- --- = 111 000 000

MANUAL OR HELP:

chmod
sudo
su
chown
chgrp
id
groups
whoami
adduser
useradd
addgroup

1. How to create a user
2. How to create a group
3. How to print real and effective user and group IDs
4. How to print the groups a user is in
5. How to print the effective userid

GENERAL RULES:

Allowed editors: vi, vim, emacs.
All your scripts will be tested on Ubuntu 20.04 LTS.
All your scripts should be exactly two lines long ($ wc -l file should print 2).
All your files should end with a new line (why?).
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing.
You are not allowed to use backticks, &&, || or ;
All your files must be executable.
