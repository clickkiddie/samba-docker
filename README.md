# samba-docker
simple samba server, host security only, gives *10.0.0.0/16* and *192.168.0.0/16* rw access to files mounted into */share*

#RUN
adjust mount in `docker-compose.yml` and start with docker-compose
```
docker-compose up -d
```