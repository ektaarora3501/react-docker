# react-docker
Creating React app inside docker container 

### to create a docker image from the mentioned docker file
sudo docker build . 

### to start the app on local machine
sudo docker run -it dockerise-react 


#### difference between container and images
Container is running instace of image. Built from docker compose.yml file
Images store all the info about the app, dependencies. Images are built from Dockerfile
