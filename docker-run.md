# Docker run 

## Beispiel (binden an ein terminal), detached

```
# before that we did
docker pull ubuntu:xenial
# image vorhanden 
docker images

docker run -t -d --name my_xenial ubuntu:xenial
# will wollen überprüfen, ob der container läuft
docker container ls 


# in den Container reinwechsel 
docker exec -it my_xenial bash 
docker exec my_xenial cat /etc/issue
# 

```
