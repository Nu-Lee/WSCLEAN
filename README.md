# Wsclean v3.3 Dockerfile
---------------------
https://wsclean.readthedocs.io/  
--------------------
You can pull images directly from Docker Hub
## Docker Hub
```
docker pull dlskadnr1209/wsclean3.3
docker run --rm -it -v data_dir:/root dlskadnr1209/wsclean3.3
```
-------------------
Or you can edit Dockerfile and build
## build Dockerfile
```
cd Docker
docker build -t wsclean ./
docker run -it -v data_dir:/root wsclean
```
