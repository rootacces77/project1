#First setup user and ssh key using playbook/add-user.yaml
#Its assumed that you have root access of servers with password or ssh key setup
#You have to setup listed vars in order for playbook to work
#user_name:		-> name of the user account
#user_public_key: 	-> your public key
#db_password:		-> password for root user

#Second step is to replace ansible_user with your user_name and ansible_port with custom sshd_port





#Things to do:
Fix NGINX
Enable ssh on Ubuntu
SSHD and useradd
Test suricata and fail2ban

Certificates
SeLinux
AppArmor
Firewall rich rules
