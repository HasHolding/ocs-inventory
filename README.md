# OCSInventory
## How to use this image
```
docker run --name mysql -e MYSQL_ROOT_PASSWORD=secret -d mysql
docker run --name ocs --link mysql:mysql -d -p 80:80 -e OCS_DBHOST=mysql -e OCS_DBNAME=ocs -e OCS_DBUSER=root -e OCS_DBPASS=secret hasholding/ocs-inventory 
```

  
# Other Docker images
https://github.com/OCSInventory-NG/OCSInventory-Docker-Image
https://github.com/zanhsieh/docker-ocs-inventory-ng
