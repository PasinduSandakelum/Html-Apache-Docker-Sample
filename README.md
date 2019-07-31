# Html-Apache-Docker-Sample
I use docker container for run a simple HTML file using apache2 server in ubuntu

For run this first we have to buid this project and run the container then we can access the port using browser


## Here are the commands that we have to run on terminal :

- docker build . -t new_docker
- docker run -it -p 8080:80 -d new_docker mysite




#### Note : 

```
Some useful commands -> See the images : docker images
                        see the containers (UP) : docker ps
                        see all the containers : docker ps -a
                        stop the container : docker stop container-id
                        start              : docker start container-id
                        remove container : docker rm -f container-id
                        remove image : docker rmi image-id
                        see the port of the container : docker port container-id
                        log into docker container : docker exec -it 4e8ed086b2c3 bash
                        
```
