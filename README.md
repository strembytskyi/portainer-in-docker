<p align="center">
  <img  src="https://cdn-images-1.medium.com/max/1200/1*xTB_v1cf8BQALOkLVid4rA.png">
</p>  
  
## About Portainer in Docker  
In this repository, you will find docker-compose files to run Portainer host and Porteiner agent for remote tracking of containers.  

## Dependencies  
> docker-compose version 1.25.1^ 

## How to  
1. `git clone https://github.com/strembytskyi/portainer-in-docker.git`  
2. `cd portainer-in-docker`  
3. Run portainer host `docker-compose -f portainer.yml up -d`  
4. Run portainer agent `docker-compose -f agent.yml up -d`  