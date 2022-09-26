# Sublime-snippets
### Snippets for bash creation

Work perfectly in Sublime Text build 4126.

Simple snippets to create quickly bash scripts for GNU/Linux.

### Object

Unify your script with this simples snippets, easy to change for everyone and for any purpose.

Remember, put the files in right location and the extension must be **.sublime-snippet** to work correctly, important for create toyr own.

### The snippets

	BashHeader

This put your own header include the she-bang and a brief description for identify the author, purpose and notes about the script function.

	Systemd-Service
	
Create a service template (unit) for a systemd service, maybe your own service os script.

	Systemd-Simple-Service
	
Crete another systemd service, more simple and suiteable.

	Create-SQL-file
	
Create a file (.sql) to execute later with:

mysql -u user -p < created-file.sql

Valid for create database, user, grant permmisionn, etc. before install software that requiere a SQL database to work or any other use, install package, etc.

	Web-Server-Example
	
Template to create a virtual Apache web server for any purpose, a simple template valid for any service, name and port, directory and rights, that´s all. Put the created file on /enable-sites/ or another .conf directory and don't forget to restart the service ;-)

	Web-Secure-Server-Example
	
Template to create a virtual Apache SSL secure web server, have instruccions to use openssl and create the necesry .key and .crt file, combined into .pem files for include in the .conf file. Read carefully.

	Loop-install-packages
	
Script to install a list off packeages included on a file named packages.cfg, rename the file if you want, packages are listed one per line.

	Linux-term-colors

Contain a list of all color you can use in script for color terminals, all color has the sames definition, one per line:

> high intensity red
> 
IRed='\033[0;91m'         # Red

	Nmed-zone
	
The script containes a complete DNS zone incluke DKIM, SPF, www, tfp, mail, smot, imao, pop3, webmal, webdad, etc. definition for your own domain, only change "mydomain.com" for your own.

	Named-addr-zone
	
Then script contains a complete reverse zone in in-addr.arpa format for "mydomain.com", by default use de private class C 192.168.1.x, change on needed.

	RedHat-eth-dhcp
	
Create a compatible cfg file for RedHat/CenOts/Rocky/Alma Linux and any RedHat derivate, modify with your needs, on boot is active by default.

	RedHat-eth-float-IP
	
Create a compatible cfg file for VLAN or float ip, modify before use.

	RedHat-eth-static-IP
	
Create a compatible cfg file with static IP in 192.168.1.x range, modify before user, on boot is active by default. Include iptables restore and vlan, iptables-persistent install packages.

	RedHat-WiFi-config
	
Create an ifcfg-ESSID file in /etc/sysconfig/network-scripts by default with WPA-PSK key, you can configure all parameters you want
also the script may included in your own script acquiere users parameters using ${parameter} to cover your our install process

	Debian-interfaces

For all Debian and dereviates.

Create a complete /etc/network/interfaces sample configuration, iptables and restart services for any use. Modify the parameters you needed

For all Debian and derivates.

	Debian-bonding
	
Create a interfaces network configuration for bondig.

	Debian-VLAN-Legacy
	
Create a interfaces network configuration for multiple IP addresses on one interface using the legacy method	

	Root-user-test
	
Script to test if user have root privileges to run your script.

	MySQL-root-pass
	
Script to change the root password and create a new root password with all host access root@%, note this is usefull in development environment but insecure on production. To execute the script, the root was haven't a password.

Resume os snippets:

1. BashHeader
2. Systemd-Service
3. Systemd-Simple-Service
4. Create-SQL-file
5. Web-Server-Example
6. Web-Secure-Server-Example
7. Loop-install-packages
8. Linux-term-colors
9. Nmed-zone
10. Named-addr-zone
11. RedHat-eth-dhcp
12. RedHat-eth-float-IP
13. RedHat-eth-static-IP
14. RedHat-WiFi-config
15. Debian-interfaces
16. Debian-bonding
17. Debian-VLAN-Legacy
18. Root-user-test
19. MySQL-root-pass

I hope these snippets help you to create scripts more efficiently and with the same aspect, add your own style, and unify the way they work. More readable, easy to maintain and enjoy the creation moment.

Thank you for your time.	

	

