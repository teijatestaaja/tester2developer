# DevOps With Docker

## Part 1

### 1.1 Getting started

```
docker container run -d nginx
docker container run -d nginx
docker container run -d nginx
docker container ls -a
docker container stop jovial_knuth
docker container stop musing_tharp
docker container ls -a
```
![1.1](/part1/1_1.png)

### 1.2 Cleanup

```
docker ps -a
docker container stop trusting_mayer
docker container rm trusting_mayer
docker container rm jovial_knuth
docker container rm trusting_mayer
docker images
docker rm image ea335
docker ps -a
docker images
```
![1.2](/part1/1_2.png)