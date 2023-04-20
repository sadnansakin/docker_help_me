# docker_help_me

### 💥 sudo docker ps --all

### 💥 sudo docker search MySQL

### 💥 sudo docker run --env MYSQL_ROOT_PASSWORD=my-secret-pw --detach mysql
- This command is used to create a container from an image

The ‘–detach’ option runs the container, and the ‘–env’ option is used to 
set the mandatory variable. 
If you do not use the ‘–name’ option,the docker will randomly assign a name to the container.


### 💥 sudo docker stop f8c52bedeecc

- The ‘docker stop’ command stops a container using the container name or its id

### 💥 sudo docker kill 09ca6feb6efc

- stop the container immediately by killing its execution.
 While the ‘docker stop’ command helps shut down the container in its own time, 
the ‘docker kill’ command stops it at once


- To check whether the container is stopped or killed, use the following command -
### 💥 sudo docker ps
