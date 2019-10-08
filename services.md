# services  
**create docker-compose.yml**  
![](image/services/services_1.png)  
`docker swarm init`  
![](image/services/services_2.png)  
`docker stack deploy -c docker-compose.yml getstartedlab`  
![](image/services/services_3.png)  
`docker service ls`  
![](image/services/services_4.png)  
`docker service ps getstartedlab_web`  
![](image/services/services_5.png)  
`docker container ls -q`  
![](image/services/services_6.png)  
`curl -4 http://localhost:4000`  
![](image/services/services_7.png)  
`docker stack deploy -c docker-compose.yml getstartedlab`  
![](image/services/services_8.png)  
`docker stack rm getstartedlab`  
![](image/services/services_9.png)  
`docker swarm leave --force`  
![](image/services/services_10.png)  
