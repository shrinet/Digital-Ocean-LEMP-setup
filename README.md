# Digital-Ocean-LEMP-setup
Setup Digitalocean LEMP setup
1- setup account
apt-get update && apt-get upgrade
dpkg-reconfigure tzdata
apt-get install fail2ban
adduser mvsusr
 usermod -aG sudo mvsusr
 rsync --archive --chown=mvsusr:mvsusr ~/.ssh /home/mvsusr
