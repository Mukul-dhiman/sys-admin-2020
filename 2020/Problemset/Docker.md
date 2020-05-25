# Docker

## Problem Statement

1. This problem deals with playing around docker (<https://www.docker.com/>), which is a containerization technology. Your task is simple.

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

2. Your college friend has an upcoming project evaluation and wants your help to host their application on the sntc server. The specifics of their application or how it works in not your concern. You decide to give your friend a small amount of access to the server. You have two options:
**Option 1:** Create a new user on the server itself for your friend so they can set up a docker container themselves. If so specify how will you set up user permissions and restrict total access.

**Option 2:** You decide to setup the docker container yourself and give him direct access to the container. But your friend is very indecisive and may consume your precious time over making you reconfigure your image configurations again and again.

Which option do you choose? How will you execute it?

## Weightage

1. 170 points
2. 30 points

## Deliverables

In your git repository whose link you will be submitting, make 3 files:

1. `Docker.md`: For Q1 here you need to write the report as to how you did this, what all resources you took help from, and what you learnt. You also need to give a link to your image on `docker store`/`docker hub`. For Q2, you need to write your solution along with the set of terminal commands if necessary.
2. `Dockerimage`: This file should have the name of the image which you set, i.e. `IMAGE_NAME`. For instance, if the name of your image is `abhigyank/testimage`, this should be the only content in this file.
3. `Docker`: Here you should add your `Dockerfile` or `docker-compose.yml` which you have used to build your image.

Remember, do not worry if you are unable to complete it, just document whatever you were able to do. :)
