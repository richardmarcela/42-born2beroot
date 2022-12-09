# 42-born2beroot
This project aims to create a virtual machine in VirtualBox under specific instructions. 
monitoring .sh - vim /usr/local/bin/monitoring.sh

sudo cat /var/log/sudo/sudo

sudo ufw status - mostra as portas permitidas pela firewall, nesse caso, so 4242

sudo ufw allow PORTA 
sudo ufw delete allow PORTA

getent group user42 - lista os usuarios que estao no grupo user42

getent group sudo - lista os usuarios que estao no grupo sudo

sudo useradd novouser 

sudo adduser novouser user42 - adc novouser a user42

sudo deluser novouser user42 - delete 

sudo addgroup novogroup

lsblk - particoes 

sudo crontab -e - ver o tempo do script
sudo crontab -r - remove o arquivo atual crontab
sudo crontab -l - mostra o conteudo atual do crontab 

sudo vim /etc/pam.d/common-password  - difok (qd mudar a passe tem que ter no minimo 7 caracteres diferente da antiga)

sudo service ssh status - status ssh e porta utilizadea

sudo visudo - restricoes do sudo

vim /etc/hostname - mudar nome do hostname e dps reboot 

hostname -I - pegar ip

ssh -p 4242 mrichard@10.11.250.218

sha1sum Born2beroot.vdi
