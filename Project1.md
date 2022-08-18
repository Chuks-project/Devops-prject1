**DOCUMENTATION OF PROJECT 1: Web Stack Implementation (lamp stack) in AWS**




**STEP 1: INSTALLING APACHE USING UBUNTU'S PACKAGE MANAGER
COMMANDS:**

- -Sudo apt update
- -Sudo apt install apache2
- -Sudo systemctl systemctl status 
- ![Install Apache](https://user-images.githubusercontent.com/65022146/185256191-7a487c71-55c0-4d1f-8490-b79407691511.png)








**STEP 2 — INSTALLING MYSQL
COMMANDS**
-sudo apt install mysql-server
-sudo mysql
-$ sudo mysql_secure_installation
![install mysql](https://user-images.githubusercontent.com/65022146/185256264-e1656e4a-5319-4c5d-bbd4-c060e94bfa93.png)










**STEP 3: Installing PHP
COMMANDS**
-sudo apt install php libapache2-mod-php php-mysql
-php -v
![Installing PHP](https://user-images.githubusercontent.com/65022146/185256321-d76ae456-0ebb-4e5d-bb43-5395955878df.png)








**STEP 4: Creating a Virtual Host for our Website Using Apache
COMMANDS:**
-sudo mkdir /var/www/projectlamp
- sudo chown -R $USER:$USER /var/www/projectlamp
- sudo vi /etc/apache2/sites-available/projectlamp.conf
- sudo ls /etc/apache2/sites-available
- sudo a2ensite projectlamp

-![Creating a Virtual Host for my Website using Apache](https://user-images.githubusercontent.com/65022146/185256130-2f72a273-69be-4915-af3c-9a84a2be800b.png)







**STEP 5: ENABLE PHP ON THE WEBSITE
COMMANDS:**
-sudo vim /etc/apache2/mods-enabled/dir.conf
-sudo systemctl reload apache2
-vim /var/www/projectlamp/index.php

![Enable PHP on the Website](https://user-images.githubusercontent.com/65022146/185256988-97cc4f06-1769-4242-834b-5285854fb7b3.png)


