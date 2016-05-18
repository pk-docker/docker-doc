1. Stop all running containers

   docker stop $(docker ps -a -q)

2. Remove all stopped containers

   docker rm $(docker ps -a -q)