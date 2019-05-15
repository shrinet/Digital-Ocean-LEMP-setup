# Digital-Ocean-LEMP-setup
Setup Digitalocean LEMP setup  
1- setup account  
apt-get update && apt-get upgrade  
dpkg-reconfigure tzdata  
apt-get install fail2ban  
adduser mvsusr  
usermod -aG sudo mvsusr  
rsync --archive --chown=mvsusr:mvsusr ~/.ssh /home/mvsusr  
sudo apt-cache show nginx  
sudo add-apt-repository ppa:nginx/stable  
sudo apt-get update  
sudo apt-get install nginx  
sudo apt-get install php7.2-fpm php7.2-cli php7.2-gd php7.2-mysql php7.2-imap php-memcached php7.2-mbstring php7.2-xml php7.2-curl php7.2-bcmath  
