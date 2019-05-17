**Build docker image**

`docker build -t nama_image`

**Run docker image**

`docker run -dp port_nya:80 nama_image`

**Push docker image to dockerHub**

`docker tag nama_image username/nama_image`

`docker push username/nama_image`
