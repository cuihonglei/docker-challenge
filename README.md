# docker-challenge

# challenge1
1. Create Dockerfile for the web service.
2. Create the docker image using the following command:  
docker build -t challange1 .
3. Run the docker image using the following command:  
docker run -d -p 8080:80 --name challange1 challange1

# challenge2
1. Create Dockerfile for the api service.
2. Create docker-compose.yml to associate the api service with the web service.
3. Start the services using the follow command:  
docker-compose up --build

# challenge3
1. Create the .env file for the db service.
2. Create docker-compose.yml to associate the api, db service with the web service.
3. Start the services using the follow command:   
docker compose up --build

# challenge4
1. Change the docker-compose.yml to add the `deploy: replicas: 3 ` section to scale up the node service from 1 to 3 instances.
2. Start the services using the follow command:   
docker compose up --build  
