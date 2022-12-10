# 42-born2beroot

## Important commands for evaluation
nano /usr/local/bin/monitoring.sh - opens monitoring.sh source code  

sudo cat /var/log/sudo/sudo.log - displays the content of sudo.log, the file that saves logs everytime a sudo command is used  

sudo ufw status - displays the current firewall status (rules i.e allowed/denied PORTS)  

sudo ufw allow <PORT> - allow a new PORT  

sudo ufw delete allow <PORT> - delete the firewall rule that allows PORT  

sudo useradd novouser - create a new user  

sudo addgroup newgroup - create a new group  

sudo adduser newuser user42 - add newuser to a group  

getent group user42/sudo - displays the users currently in the group  

sudo deluser newuser user42 - removes newuser from a group  

lsblk - displays the disk partitions  

sudo crontab -e - check if the monitoring script is scheduled on crontab  

sudo crontab -r - remove the current crontab tasks  

sudo crontab -l - show the current crontab tasks  

sudo nano /etc/pam.d/common-password  - password policy   

sudo service ssh status - show the status of ssh  

sudo visudo - sudo restrictions  

nano /etc/hostname - change the hostname  

hostname -I - get VM's ip  

ssh -p 4242 <user>@<VM's ip> - connect Host terminal with the VM  

sha1sum <machine_name>.vdi - generate the signature
