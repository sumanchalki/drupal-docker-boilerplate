Following are the commands to make the containers up & running.
1. Edit docker-compose.yml and change the "container_name". Use a name related to project name.
2. docker-compose up -d
For production the command will be -
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d
File docker-compose.override.yml contains the configuration for DEV env.