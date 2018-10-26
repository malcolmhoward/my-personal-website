# my-personal-website
This is a public/open-source project to document and share my journey developing a personal website.

Goals for this site include:
  - Displaying resume/CV
  - Blogging about various personal projects, community service initiatives, and other events/activities of interest
  - Docker it.

# Docker Command Cheat Sheet
############################
# "sudo docker build -t image_name ."  # Build a docker image named image_name using the Dockefile in the current directory
# "sudo docker run -d -p 8005:8001 --name container_name image_name"  # Example command to start a container with an image
# "sudo docker run -d -p host_port:container_port --name container_name image_name"  # Start a docker container named container_name based off of a docker image named image_name
# "sudo docker stop container_name"  # Stop docker container named container_name (needed for graceful deletion)
# "sudo docker rm container_name"  # Remove docker container named container_name
# "sudo docker image rm image_name"  # Remove docker image named image_name
# "sudo docker ps"  # list all RUNNING containers
# "sudo docker ps --all"  # list all containers
# https://docs.docker.com/engine/reference/commandline/run/#options
# -d or --detach runs the container in the background
# -p or --publish publishes a container's port(s) to the host
# TODO: Figure out how to mount a volume to the container or save the container on exit, so that any data can persist
# "docker-machine create machine_name"  # Create a docker machine named machine_name
