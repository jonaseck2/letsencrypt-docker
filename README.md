# letsencrypt-docker

letsencrypt docker box configured for noninteractive priovisioning of certificates.

update email and domains in ```cli.ini``` and execute ```docker-compose up``` or ```docker-compose run letsencrypt```. The generated certs are placed in ```/etc/letsencrypt```. 

renewing is performed by executing ```docker-compose run letsencrypt renew```
