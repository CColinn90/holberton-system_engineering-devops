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
