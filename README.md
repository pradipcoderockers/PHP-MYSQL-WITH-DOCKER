# PHP-MYSQL-WITH-DOCKER

## Local Setup

- Install [Docker](https://docs.docker.com/engine/installation/) for your OS. 

- Checkout this repo. Please notice that, if your OS is Windows, then you need to have at least version 10 (otherwise Docker can raise some exceptions); moreover ,before doing the checkout, please be sure to run the following git command:
  ```
  git config --global core.autocrlf input
  ```
  This command avoids the EOL (End Of Line) replacement. The latter is due to git which automatically reformat the file based on the current OS. As a conseguence, Linux-style EOL are replaced with Windows-style EOL.

- Enter the Terminal or the Command Prompt at root level of the project

- Run `docker-compose up` to first build and then run the project (it tooks several minutes the first time you run the command).

- Go to [http://localhost:8080/](http://127.0.0.1:8080/) to see the PHP running app.


## Some import docker command that help you to access docker #######
-- Running docker ps --no-trunc showing list linked containers.

-- docker-container-prune - Remove all stopped containers

--  docker exec -it <name of container file> /bin/bash to ssh inside docker container




