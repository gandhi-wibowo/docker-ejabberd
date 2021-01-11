# WTF is this ?
*This is just my docker config, for my develop purpose*

## RUN

### create docker container
> docker-compose up -d

### create admin user
> docker exec -it ejabberd bin/ejabberdctl register admin localhost passw0rd

### then ?
you can access http admin from localhost:5280/admin (username : admin, password : passw0rd)
