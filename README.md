# docker-webmin
Minimum working version of Webmin in Docker

## Building & running the image
```
git clone https://github.com/kipjr/docker-webmin.git
cd docker-webmin
echo -n "somepassword" > ./secrets
docker-compose up --build --force-recreate -d
```

## Stopping the container
```
docker-compose down
```

## Log into webmin and manage your server
```
http://hostname.or.ip:10000
```
