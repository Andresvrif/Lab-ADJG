### TIPS

Para iniciar el contenedor mysql:

```docker run -it --name srvdb -e MYSQL_ROOT_PASSWORD=1234 --volume /home/docker/srvdb:/var/lib/mysql -d mysql:5.7```
