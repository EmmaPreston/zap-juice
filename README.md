# zap-juice
A docker composer file for easy install and use of owasp's Zap proxy and juice shop the vulnerable webapp.

- Clone the respository 
- Go into the zap-juice directory
- Run ```docker-compose up -d```

Zap: Navigate to http://127.0.0.1:8080/?anonym=true&app=ZAP \
Juice Shop: Navigate to http://127.0.0.1:8082/#/

Docker Tips:
See docker containers currently running along with the container id ```docker ps```
To kill a docker container ```docker kill {container id}```
To view logs on a running container ```docker logs {container id}```
