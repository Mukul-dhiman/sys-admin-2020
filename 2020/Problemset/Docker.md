# Docker

## Problem Statement

This problem deals with playing around docker (<https://www.docker.com/>), which is a containerization technology. Your task is simple.

Upload an docker image to [docker store](https://store.docker.com/) or [docker hub](https://hub.docker.com/) with your username. 

The image should have the application [baat-cheet](https://github.com/KamandPrompt/baat-cheet) running at port 3000 of the container.

The image should execute a command which shows the logs of the node application.


So when one runs your image using `docker run IMAGE_NAME`, this is what they should see on their machine's terminal:

```txt
Listening on port 3000
...
...
logs
...
...
```

Anybody around the world if has to do this, he must be able to type a simple command `docker run IMAGE_NAME` and should see this output on his terminal. Here `IMAGE_NAME` is the name of the image which you set.


## Weightage

150 points

## Deliverables

In your git repository whose link you will be submitting, make 2 files:

1. `Docker.md`: Here you need to write the report as to how you did this, what all resources you took help from, and what you learnt. You also need to give a link to your image on `docker store`/`docker hub`.
2. `Dockerimage`: This file should have the name of the image which you set, i.e. `IMAGE_NAME`. For instance, if the name of your image is `abhigyank/testimage`, this should be the only content in this file.
3. `Docker`: Here you should add your `Dockerfile` or `docker-compose.yml` which you have used to build your image.

Remember, do not worry if you are unable to complete it, just document whatever you were able to do. :) 
