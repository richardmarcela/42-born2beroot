# 42-born2beroot

## Important commands for evaluation
nano /usr/local/bin/monitoring.sh - monitoring.sh 

sudo cat /var/log/sudo/sudo.log - log everytime a sudo command is used 

sudo ufw status - show the allowed ports by firewall, in this case only 4242

sudo ufw allow PORT - allow a new port 

sudo ufw delete allow PORT - delete the rule that allows port

sudo useradd novouser - create a new user

sudo addgroup novogroup - create a new group

sudo adduser novouser user42 - add user to group

getent group user42/sudo - get the users in the group

sudo deluser novouser user42 - delete user of a group 

lsblk - show the disk partitions 

sudo crontab -e - check if the monitoring script is scheduled

sudo crontab -r - remove the current crontab

sudo crontab -l - show the current crontab

sudo nano /etc/pam.d/common-password  - password policy 

sudo service ssh status - show the status of ssh 

sudo visudo - sudo restrictions

nano /etc/hostname - change the hostname 

hostname -I - get ip

ssh -p 4242 mrichard@10.11.250.218 - connect terminal of pc with the vm

sha1sum Born2beroot.vdi - generate the signature
