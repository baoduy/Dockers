# Run a docker app

- 1. install docker-app [here](https://github.com/docker/app/releases)
- 2. pull the image from the repository.
- 3. run the command: `docker-app render fishe-devevn.dockerapp -f dev.yml | docker-compose -f - up -d`
     which dev.yml contains the environment parameters as below

```yml
HOST_NAME: 192.168.1.19 #update this one to your host IP Address
```
