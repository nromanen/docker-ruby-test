    1. Create a Dockerfile in the 'api' directory and name it Dockerfile-dev.
    2. Use nodejs version 16 as the base image in the Dockerfile.
    3. Configure the container to run on port 3080.
    4. Set the working directory to /usr/src/app/api in the Dockerfile.

    1. Create a Dockerfile in the 'ui' directory and name it Dockerfile-dev.
    2. Use nodejs version 16 as the base image in the Dockerfile.
    3. Configure the container to run on port 4201.
    4. Set the working directory to /usr/src/app/app-ui/ in the Dockerfile.

    1. In root directory create a new file named 'docker-compose.yml'.
    2. Define the first service named 'nodejs-server' in the Docker Compose file.
    3. Specify the Dockerfile for this service as 'Dockerfile-dev' located in the 'api' directory.
    4. Set the service to run on port 3080. 

    5. Define the second service named 'angular-ui' in the Docker Compose file.
    6. Specify the Dockerfile for this service as 'Dockerfile-dev' located in the 'ui' directory.
    7. Set the service to run on port 4201.
    