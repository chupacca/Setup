List of commands: https://docs.docker.com/engine/reference/commandline/image_ls/

1. Pull an image:
  + Visit Docker Hub for published ones
```
sudo docker pull [IMG]
```
Example: `sudo docker pull mkodockx/docker-clamav`

2. Run an image:
```
sudo docker run --rm -it [IMG]
```
Example: `sudo docker run --rm -it  mkodockx/docker-clamav`

3. List images:
```
sudo docker image ls
```

4. Remove an image:
```
sudo docker image rm <img_name>
```
Example: `sudo docker image rm mkodockx/docker-clamav:buster-slim

