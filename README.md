# Vulnerable Web Application V1.0

![VulnWeb](https://github.com/hummingbirdscyber/Vulnerable-Web-Application/blob/master/Resources/VulnWeb.png)

<h2>Installation Guide</h2>

If you want to run this tool, first of all you need to download web server solution like "xampp"- you can download xampp from
[Xampp](https://www.apachefriends.org/tr/download.html). After your installation;

For Windows you need to copy the files into the xampp/htdocs folder.

For Mac Os  you need to install mampp and  copy the files into the mamp/htdocs folder.
[Mampp](https://www.mamp.info/en/downloads/)

For Linux after download our files first you need to open apache server and copy the files to /var/www/html

<b>Other Configurations:</b>

The php.ini file should be  altered. You can find the location of your  php.ini file under the folder which php is installed.
* allow_url_include = on - Allows for Remote File Inclusion
* allow_url_fopen = on - Allows for Remote File Inclusion
* safe_mode = off - (If PHP <= v5.4) Allows for SQL Injection
* magic_quotes_gpc = off - (If PHP <= v5.4) Allows for SQL Injection

<b>Installation</b>

After all these configurations, firstly, open Xampp Control Panel and start Apache,MySQL. Your MySQL credentials have to be default.<b>[username:root <-> password:""]</b> Then open up our index.php file in the <b>Vulnerable Web Application</b> directory. Follow the directions and create database. If you messed up with database, you can reset the database. If database is ready, you can go to homepage and start hacking.

test on license branch
  
