Checkpoint 1:

	sudo stands for "super-user do" which means run the following command as root i.e with admin privileges, which can be dangerous for the system since there are no protections against user mistakes or malicious purposes, root has complete control over the entire system.
    
	apt-get is used to download and install packages from the specific linux distribution. It can also be used to update packages. Should be run as root to install packages.

Checkpoint 4:

	2) I used the mv command, prepended by sudo since I was changing a file owned by root as a non-root user.

Checkpoint 6:

	2) Changing the group that owns the directories storage/ and ./bootstrap/cache/ from the root group to the www-data storage group, recursively (through the -R flag)
	3) Changing the permissions for the user and group, giving both read, write, and execute permissions for the following directories: storage/ and bootstrap/cache/.

Commands to run:

	sudo apt update
	sudo apt install apache3 default-mysql-server php-mysql php libapache2-mod-php php-pear curl php-curl php-cli git
	cl
	a3enmod rewrite
	sudo systemctl restart apache3.service
	clear
	sudo apt install libapache3-mod-wsgi-py3
	a3enmod
	clear
	sudo a3enmod
	cl
	cd /var/www/html
	ls
	cl
	pwd
	cl
	CL
	cl
	cd /etc
	vim ssh/sshd_config
	cl
	sudo a3enmod rewrite
	cl
	sudo a3enmod rewrite
	cl
	sudo systemctl restart apache3.service
	cl
	cd /var/www/html
	ls
	cl
	pwd
	sudo a3enmod rewrite
	cl
	sudo systemctl restart apache3.service
	cl
	cd /var/www/html
	sudo git clone https://github.com/ElioaChukri/stunning-laravel.git
	cd stunning-laravel
	ls
	cl
	sudo su
	cl
	composer.phar install
	sudo composer.phar install
	ls -a
	c
	cl
	pwd
	mv .env.example .env
	sudo su
	cd /var/www/html
	ls
	cd stunning-laravel
																																																								1,1           Top
