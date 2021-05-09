# WTF is this ?
*This is just my docker config, for my develop purpose*

## RUN

### create docker container
> docker-compose up -d
> after all container run, restart ejabberd container (its look like when first run, mysql not loaded)

### create admin user
> docker exec -it ejabberd bin/ejabberdctl register admin localhost passw0rd

### then ?
you can access http admin from localhost:5280/admin (username : admin, password : passw0rd)

### Note
mysql account "root|p4ssw0Rd"
ejabberd web admin "admin|passw0rd"

This stuf is enable mode rest api to all.
