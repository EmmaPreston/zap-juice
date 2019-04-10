# zap-juice
A docker compose file for easy install of OWASPs ZAP proxy and Juice Shop the vulnerable webapp.

- Clone the respository ```git clone https://github.com/EmmaPreston/zap-juice.git ```
- Go into the zap-juice directory e.g ```cd zap-juice```
- Run ```docker-compose up -d```

Zap: Navigate to http://127.0.0.1:8080/?anonym=true&app=ZAP \
Juice Shop: Navigate to http://127.0.0.1:8082/#/

Docker Tips:
See docker containers currently running along with the container id ```docker ps``` \
To kill a docker container ```docker kill {container id}```  \
To view logs on a running container ```docker logs {container id}``` 
