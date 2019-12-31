make .env file in rood directory and set DOCUMENT_ROOTDIR, USER_NAME, DOMAIN_NAME, 
MYSQL_USER, MYSQL_PASSWORD like .envexample file.

1. `docker-compose up -d`
2. `docker exec -it xserver bash`
3. after you enter the container, you should run `systemctl restart httpd`

if you are using `docker-machine`, you can inspect ip address using `docker-machine ip {your machine-name}`.