# Commands

_|| && ;;_
_| & ;_
_fg bg_
_lt eq gt_

## ls
list files and directories
 -a => list all normal and hidden files and directories
 -l => list view
 -t => time
 -h =>
 
## mkdir
make directories
mkdir -P =>

## rmdir
remove empty directory

## touch
create a new empty file

## rm
remove file
rm -rf => delete not empty directories

## cd
change directory
cd .. => go to parent directory
cd parent/child => یک راست به دایرکتوری زیرین میرود
cd ../.. => go to 2 level up directory
cd ~ => go to home directory
cd - => last active directory

## pwd
print working directory

## echo
print on bash
echo ~ => show home

## Od -vAn -N4 -tu4 < /dev/urandom
giving a random number

## tree
for showing directories tree and sub directories and files
tree -d -L 1 /root => show 1 level deep in root directory

## su

su -c =>
su -[user] =>

## du

du -h --max-depth=1 /root =>

## useradd

## passwd

## userdel

## groupadd

## groupdel

## id

## usermod

usermod -G =>

## chown
change owner
chown [user] [filename]
chown [user]:[group] [filename]

## chmod

## chgrp
change group

## cp
copy command
cp [sourcefile] [distationdirectory]

## cat

##  wc
word count

## sort
sorting command

## uniq
looking for unique parameters

## tar
compress files and directories
tar -cv [directory] =>

## gzip

## history
show 1000 last command

## clear
clean screen you can also use Ctrl+L

## grep
find a word or pattern in a file
-i => no matter capital or small
-v => remove
-o => only

## egrep
it's same az grep -E

## while

## loop

## for

## systemctl
systemctl list-units
systemctl list-unit-files --type=service
systemctl status [service]
systemctl start [service]
systemctl stop [service]
systemctl disable [service]
systemctl enable [service]

## hostnamectl
hostname status

## ifup
make a ethernet connection On or up

## ifdown
make a ethernet connection Off or down

## ip

 ip a =>
 ip route show =>
 
## yum
 
 yum list installed
 yum check -update
 yum update -y => update all with YES
 yum search [package name]
 yum install [package name]
 
## rpm -ql [package name]
 find name and directory of files of an installed package
 
## rpm -Uvh [package name]
 
## uname -r
 
## less
 
## firewall-cmd --list-all
## firewall-cmd --permenant --add-service [service name]
## firewall-cmd --permenant --remove-service [service name]
## firewall-cmd --reload
## firewall-cmd --permenant --add-port=12345/tcp
## firewall-cmd --permenant --remove-port=12345/udp
  
## ACL
  Access Control List
  getfacl [file]
  setfacl [file]
  example: setfacl -m user:[user]:[rwx] [file]
  example: setfacl -x user:[group]:[rwx] [file]
  
## setuid
  set user id
## setgid
  set group id
## sticky bit