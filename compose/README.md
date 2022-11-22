Make sure to add the mirror registry to your docker daemon json. If you are using docker desktop just add it under 'Preferences -> Docker Engine'
```
  "registry-mirrors": [
    "https://registry-1.docker.io"
  ]
```
Then build the images and run it with:
```shell
docker-compose build
docker-compose up
```