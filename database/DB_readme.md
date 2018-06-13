## My SQL Database Setup
### Docker Setup

```shell
$ docker pull mysql
$ docker run -d --name mysql_java -p 3306:3306 -v /Users/dockervol/mysql:/var/lib/mysql -e 'MYSQL_ROOT_PASSWORD=tiger' mysql:5.7.22
$ docker exec -it mysql_java bash
$ mysql -uroot -p
```
