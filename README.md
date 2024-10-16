# install-docker-manjaro-arch-linux

## Install docker
```
pamac install docker
```

## Install docker-compose
```
pamac install docker-compose
```

## Start docker service
```
sudo systemctl start docker.service
```

## Stop docker service
```
sudo systemctl stop docker.service
```

## Enable docker service
```
sudo systemctl enable docker.service
```

## Create docker group
```
sudo groupadd docker
```

## Add user to docker group
```
sudo usermod -aG docker $USER
```

## Log in to the new group using the newgrp command
```
newgrp docker
```

### You have now successfully set up Docker on Manjaro.
