0. My name is Betty  

-You should use exactly 8 characters for your command (+1 character for the new line)

-You can assume that the user betty will exist when we will run your script

julien@ubuntu:/tmp/h$ tail -1 0-iam_betty | wc -c

9

julien@ubuntu:/tmp/h$

------------------------------------

1. Who am I


Write a script that prints the effective username of the current user.

julien@ubuntu:/tmp/h$ ./1-who_am_i

julien

julien@ubuntu:/tmp/h$ 

---------------------------------------

2. Groups

Script that prints all the groups the current user is part of.

julien@ubuntu:/tmp/h$ ./2-groups

julien adm cdrom sudo dip plugdev lpadmin sambashare

julien@ubuntu:/tmp/h$


Note: depending on the user, you will get a different output.

---------------------------------------------

New owner

script that changes the owner of the file hello to the user betty.

ulien@ubuntu:/tmp/h$ ls -l

total 4

-rwxrw-r-- 1 julien julien 30 Sep 20 14:23 3-new_owner

-rw-rw-r-- 1 julien julien  0 Sep 20 14:18 hello

julien@ubuntu:/tmp/h$ sudo ./3-new_owner 

julien@ubuntu:/tmp/h$ ls -l

total 4

-rwxrw-r-- 1 julien julien 30 Sep 20 14:23 3-new_owner

-rw-rw-r-- 1 betty  julien  0 Sep 20 14:18 hello

julien@ubuntu:/tmp/h$

