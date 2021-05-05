# Commands

find . -type d -exec chmod 755 {} \; && find . -type f -exec chmod 644 {} \;
php artisan make:model --migration --controller test
php artisan make:model --migration --controller --resource Amenity

<!-- set the folder permission -->

sudo chown -R www-data:www-data storage/*
sudo chown -R daemon:daemon storage/ 
sudo chown -R bitnami:www-data public/*


#aws

<!-- terminal connect -->
sudo chmod -R 400 LightsailDefaultKey-us-east-2.pem

ssh -L 8888:127.0.0.1:80 -i LightsailDefaultKey-us-west-2.pem bitnami@18.189.182.158

Command :- ssh -L 8000:127.0.0.1:80 USER_NAME@YOUR_IP_ADDRESS
phpmyadmin :- http://localhost:8000/phpmyadmin/

--

#PHP version change through htaccess
<!-- media library conversation issues -->
AddHandler application/x-httpd-php74 .php


