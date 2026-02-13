#User & Group management commands

sudo
useradd
whoami
su
passwd
userdel
groupadd -m
gpasswd -a, -m
groupdel


useradd (adds new user to system)
-sudo useradd -m jetha (add user named username to system)
-sudo passwd jetha (used to set password for user)
-su jetha(switch user)

-cat /etc/passwd (lists all users)

userdel (removes a user)
-sudo userdel jetha
-sudo userdel -f jetha (forces user removal)

groupadd
-sudo groupadd devops (add grp named devops)
-cat /etc/group (lists all groups)
-sudo gpasswd -a jetha devops (adds jetha to devops)
-sudo useradd -m bhide
-sudo groupadd tester
-sudo gpasswd -a bhide tester 

-sudo groupdel tester (deletes the tester group)



