# docker-compose-up
Reference material for https://medium.com/@zhao.li/how-to-understand-running-containers-with-docker-compose-a8160b487a98

Getting Started
---------------
1. install docker
1. install docker-compose
1. clone repository: `git clone --recursive https://github.com/zhao-lin-li/docker-compose-up.git`
1. run `docker-compose up` to run the image

To stop the container, press `CTRL-C` or issue `docker-compose down`

Verify Image
------------
```shell
$ docker-compose ps
Name                 Command       State           Ports         
--------------------------------------------------------------------------
docker-compose-up_app_1   catalina.sh run   Up      0.0.0.0:8081->8080/tcp
```
