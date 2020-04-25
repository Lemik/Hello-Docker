# Hello-Docker
this is a simple docker app that will print Vancouver time 

to run it use docker 
#build 
docker build  -t hello-docker .
#run
docker run --rm --name Hello-Docker  -p 8080:8080 hello-docker 
