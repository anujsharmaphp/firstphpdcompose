# firstphpdcompose
Please set up Docker desktop properly on windows OS.

This is compose file for first php docker application 




Please git clone in your local : https://github.com/anujsharmaphp/firstphpdcompose.git

Download all 3 images to run the project.<br /><br />

docker pull anujarcanetinmen/first-php:firstphpimage <br />
docker pull anujarcanetinmen/mymysql:V1.0<br />
docker pull anujarcanetinmen/myphpmyadmin:V1.0<br />

Run below command in same folder where docker-compose.yml file is :<br />
docker-compose up -d 

Open http://localhost:8080 for phpmyadmin  
server :mydb
user: MYSQL_USER
pass : MYSQL_ROOT_PASSWORD

Import db/db.sql to MYSQL_DATABASE

Open http://localhost:8000/ for php application


