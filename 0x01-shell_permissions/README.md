Project 0x01. Shell, Permissions By Gibson Ngulube

09 March, 2023. 10:20 PM. 

1. A bash script that switches from current user to the user 'Betty'.

#!/bin/bash  
su - Betty

2. A bash script that prints out the current user.

#!/bin/bash
whoami

3. A bash scripts that lists all groups the current user is in.

#!/bin/bash
groups

4. A bash script that changes file ownership.

#!/bin/bash
sudo chown betty hello

5. A bash script that creates a new empty file 'hello'.

#!/bin/bash
touch hello

6.A bash script to assign exe permissions to the owner of a file.

#!/bin/bash
chmod 744 hello 
