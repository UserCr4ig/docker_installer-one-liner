### Install Docker

`curl -fsSL get.docker.com -o get-docker.sh && sh get-docker.sh`

### Install Docker and Portainer

`curl -fsSL get.docker.com -o get-docker.sh && sh get-docker.sh && sudo docker run docker run -d -p 8000:8000 -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest`


  #### And add the best template for Portainer.
  
  https://github.com/Lissy93/portainer-templates
