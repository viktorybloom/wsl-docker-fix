# wsl-docker-fix
In cases where docker refuses to connect via wsl and throws the following `Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?` run the following to re/start the docker daemon: 

`sudo dockerd > /dev/null 2>&1 &`


