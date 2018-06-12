# docker-ubuntu-wordpress-mysql-php7-nginx

Step 1. Replace **password** string in docker-compose.yml file with your own **secret password** and also change in **wp-config.php** file under wordpress directory. Currently wordpress DB user is **webuser** but we can also chnage both in docker-compose.yml file and wp-config.php file.

Step 2. Run $ docker-compose up -d

Step 3. Visit localhost or server IP or domain url on browser and install wordpress.

Step 4. To Stop all Containers and remove their exsting volumes then run the following commands on terminal :-->

        docker-compose down -v
