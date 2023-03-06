### Docker Commands

<mark>**docker version**</mark> ► Get the currently installed version of docker

<mark>**docker pull <image name>**</mark> ► To pull images from the docker repository
  
<mark>**docker run -it -d <image name>**</mark> ► To create a container from an image

<mark>**docker ps**</mark> ► To list the running containers
  
<mark>**docker ps -a**</mark> ► To show all the running and exited containers
  
<mark>**docker exec -it <container id> bash**</mark> ► To access the running container
  
<mark>**docker stop <container id>**</mark> ► To stops a running container
  
<mark>**docker kill <container id>**</mark> ► This command kills the container by stopping its execution immediately
  
<mark>*docker commit <conatainer id> <username/imagename>**</mark> ► To create a new image of an edited container on the local system
  
<mark>**docker login**</mark> ► To login to the docker hub repository
  
<mark>**docker push <username/image name>**</mark> ► To push an image to the docker hub repository
  
<mark>**docker images**</mark> ► To lists all the locally stored docker images
  
<mark>**docker rm <container id>**</mark> ► To delete a stopped container
  
<mark>**docker rmi <image-id>**</mark> ► To delete an image from local storage
  
<mark>**docker build <path to docker file><image-id>**</mark> ► To build an image from a specified docker file
