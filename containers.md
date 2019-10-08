# containers  
**create Dockerfile**  
![](image/containers/containers_1.png)  
![](image/containers/containers_2.png)  
**create app.py**  
![](image/containers/containers_3.png)  
`docker build --tag=friendlyhello .`  
![](image/containers/containers_4.png)  
`docker image ls`  
![](image/containers/containers_5.png)  
`docker run -p 4000:80 friendlyhello`  
![](image/containers/containers_6.png)  
`curl http://localhost:4000`  
![](image/containers/containers_7.png)  
`docker login`  
![](image/containers/containers_8.png)  
`docker image ls`  
![](image/containers/containers_9.png)  
`docker push bigggreenapple/get-started`  
![](image/containers/containers_10.png)  
