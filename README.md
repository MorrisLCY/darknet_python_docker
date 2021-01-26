# darknet_python_docker

# Here is my dockerhub
https://hub.docker.com/r/morriscy0910/darknet_python

# Darknet Version
https://github.com/AlexeyAB/darknet

# My gpu Card 
GeForce RTX 2070ti

# How To Use:

1. Pull first
(sudo docker pull morriscy0910/darknet_python:cuda10.0-cudnn7-devel-ubuntu18.04-openCVpython4.1.1-cxOracle-AlexeyVersion)

2. sudo docker run -it --runtime=nvidia --volume ${PWD}/output:/home/darknet/output morriscy0910/darknet_python:cuda10.0-cudnn7-devel-ubuntu18.04-openCVpython4.1.1-cxOracle-AlexeyVersion

3. Now, You're In My Images

4. cd /home/darknet

5. /usr/bin/python3.6 Car_Detection.py

6. Now, Check your Host directory will have a output file that Inside will have a result.jpg
