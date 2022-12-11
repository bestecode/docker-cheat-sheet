# Cheat Sheet

### General Commands
- Starting Docker Deamon 
 - `docker -d`
- Inspecting Logs
 - `docker logs <containerId>`
- Getting Help
 - `docker --help`
- Display System-Wide Information
 - `docker info`
- Stats Of Running Containers
 - `docker stats`
- Getting Detailed Info About Object
 - `docker inspect {name}`
- Showing Port Of A Container
 - `docker port {container}`
- Docker Stats Of Running Containers
 - `docker stats`
- Docker Stats Of Running Containers
 - `docker stats`

### Image Commands
- Running New Image
 - `docker run -p host : containerport {image}`
- Downloading An Image
 - `docker pull {image}`
- Pushing Image To A Repo
 - `docker push {image}`
- Deleting An Image
 - `docker rmi {image}`
- Listing All Images
 - `docker images`
- Build An Image From Dockerfile 
 - `docker build {directory}`

### Container Commands
- Listing Running Containers
 - `docker ps`
- Listing All Containers
 - `docker ps -a`
- Deleting Container 
 - `docker rm {container}`
- Starting Stopped Container 
 - `docker start {container}`
- Stopping Running Container
 - `docker stop {container}`
- Copy A File From Container To Host
 - `docker cp container:source target`
- Starting A Shell Inside A Running Container
 - `docker exec it container executable`
