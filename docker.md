## docker

docker images
	//list of images to start a container from
	
docker ps	
	//list of containers running

docker stop --time=10 mariadbtest
	//docker stop SIGTERM signal - after timeout kill: SIGKILL signal
	
docker kill mariadbtest

docker rm mariadbtest	
	-v
	//remove - -v : remove with volume

docker pause name
	//freeze a docker

docker exec -it mariadbtest bash
	//access the container


## docker-compose

docker-compose pull
	//pull necessary images

docker-compose up --no-recreate
	//create container ONLY if it doesn't exist
	
docker-compose up -d
	//to craete it if it doesn't exist or recreate it if config has changed
	//Detached mode - runs in background

docker-compose -f docker-compose.yml up -d

docer-compose kill <service>
	//SIGKILL - signal
