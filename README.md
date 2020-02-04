# A Cloud9 docker image based on Ubuntu 20.04 (Focal)

## Base Docker Image
[Ubuntu](https://hub.docker.com/_/ubuntu) 20.04 (x64)

## Get the image from Docker Hub
```
docker pull fullaxx/cloud9-focal
```

## Run the image on port 80
```
docker run -d -p 80:80 fullaxx/cloud9-focal
```

## Save your Cloud9 workspace on the host
```
docker run -d -p 80:80 -v /your/path/c9ws/:/c9ws/ fullaxx/cloud9-focal
```

## Build it locally using the github repository
```
docker build -t="fullaxx/cloud9-focal" github.com/Fullaxx/cloud9-focal
```
