in order to access docker tensorflow installation:

sudo docker run -it -p 8888:8888 gcr.io/tensorflow/tensorflow

type something like:
http://127.0.0.1:8888/?token=ae6a5236fc690a782a2c83d91d9827e95b4db2d41f46ac07


taken from:
https://hub.docker.com/r/waleedka/modern-deep-learning/

for python file with python3.5 and some other updated libraries:
docker pull waleedka/modern-deep-learning

to run:
docker run -it -p 8888:8888 -p 6006:6006 -v ~/:/host waleedka/modern-deep-learning

or, use:
https://github.com/saiprashanths/dl-docker