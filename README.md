# Sublime-snippets
### Snippets for bash creation

Work perfectly in Sublime Text build 4126.

Simple snippets to create quickly bash scripts for GNU/Linux.

### Object

Unify your script with this simples snippets, easy to change for everyone and for any purpose.

Remember, put the files in right location and the extension must be **.sublime-snippet** to work correctly, important for create toyr own.

### The snippets

	BashHeader.sublime-snippet

This put your own header include the she-bang and a brief description for identify the author, purpose and notes about the script function.

	Systemd-Service.sublime-snippet
	
Create a service template (unit) for a systemd service, maybe your own service os script.

	Systemd-Simple-Service.sublime-snippet
	
Crete another systemd service, more simple and suiteable.

	Create-SQL-file.sublime-snippet
	
Create a file (.sql) to execute later with:

mysql -u user -p < created-file.sql

Valid for create database, user, grant permmisionn, etc. before install software that requiere a SQL database to work.

	Web-Server-Example.sublime-snippet
	
Template to create a virtual Apache web server for any purpose, a simple template valid for any service, name and port, directory and rights, that´s all. Put the created file on /enable-sites/ or another .conf directory and don't forget to restart the service ;-)

	Web-Secure-Server-Example
	
Template to create a virtual Apache SSL secure web server, have instruccions to use openssl and create the necesry .key and .crt file, combined into .pem files for include in the .conf file. Read carefully.

I hope these snippets help you to create scripts more efficiently and with the same aspect, add your own style, and unify the way they work. More readable, easy to maintain and enjoy the creation moment.

Thank you for your time.	

	

