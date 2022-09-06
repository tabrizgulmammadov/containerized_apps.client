# DotNet Client


### How to run application as a container in your pc?
- Clone the project from master branch to you pc
- Go to the repository of the project and run 'docker-compose -f .\docker-compose.yml -f .\docker-compose.override.yml up -d' command
- Check existing of created container named 'dotnetclient' using 'docker container ps' command
- Enter 'http://localhost:8000/swagger/index.html' url where you can see swagger
- You can see entered texts from the terminal (powershell, command prompt et.) using 'docker logs <container_id>' or from Docker Desktop application
