# how to find latest version
FROM ubuntu:latest

# This is all you need to build and run the container
# docker build .

# This mounts a folder into the docker image, and runs the image in interactive mode (like a shell)
# We can find the mounted folder in /mnt
#docker run -v /Users/zachcristol/Documents/Developer/Zach/DockerTut:/mnt -it 7825af3e6bb4



# This downloads the indexes of packages (that's how lean it is)
# Without these run commands, we can  
# We need the y otherwise it will prompt for a yes and time out
RUN apt-get update && apt-get install -y vim
