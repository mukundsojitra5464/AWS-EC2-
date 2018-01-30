# AWS-EC2-Commands  


######### This command copy file ######### 
- sudo cp /var/log/nginx/access.log-20171129.gz /var/www/html/


######### This command for check spaces useses ##########
1) df -h
2) du -ah /var/log/nginx/

######### When ngnix permission denied Command ###########
- sudo su

######### List of directory command #############
1) ls
2) ls -lh (For list of files with size)

######### NGinx Server Command ###########

*******First need to check server status using below command  
- sudo service nginx status

*******Second :- 
- sudo service nginx restart 

*******If restart is any issue 
- sudo  service nginx start
- sudo  service nginx stop


######### Apache Command ###########

*******First need to check server status using below command  
- sudo /etc/init.d/httpd status

******Apache Start
- sudo /etc/init.d/httpd start

******Apache Stop
- sudo /etc/init.d/httpd stop

******Apache restart
- sudo /etc/init.d/httpd restart


######### fastcgi Command ###########

******fastcgi restart
- sudo service php-fpm restart

******fastcgi check status
- sudo service php-fpm status


########### CronTab Command #############

********** Crontab status
- service crond status

********** Crontab restart
- sudo service crond restart

********** Crontab stop
- service crond stop

********** Crontab start
- service crond start

***********First run this command for change in cron
1) crontab -e
2) sudo nano crontab -e 
3) nano crontab -e












