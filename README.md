TO DELETE THE APACHE2 SERVER
# iptables -A INPUT -p tcp --dport 8080 -j ACCEPT
# systemctl status jenkins.service
# cat /var/lib/jenkins/secrets/initialAdminPassword
command to use uninstall apache2
service apache2 stop
 apt-get remove apache2
 apt remove apache2
HOW TO INSTALL APACHE2 ON SERVER
apt update
apt install apache2
systemctl status apache2
service apache2 status
service apache2 start
