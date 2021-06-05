# DockerHelloWorldWordpress
This is code is toy-example on how to use Docker on Ubuntu (or a related Linux distribution). It may work on other systems although it was not tested on them. The purpose of this code is to help Researchers learn the basics of Docker. Of course, it can also benefit Software Developers. The code is very simple. It just prints to the console:

``Possible Nucleotides for a DNA `Sequence: 'A', 'C', 'T', 'G'``

The code is simple so focus can remain on Docker.
## Installing Python
You can find instructions on installing Python on [https://www.python.org/downloads/](https://www.python.org/downloads/)

## Running code
To run the code, open a console and navigate to where you have the code on your local machine. And then just run:
``python app.py``

## Code components
The components of the code are:
- app.py
- Dockerfile

Discussion of the other files are outside the scope of this tutorial. You can use your favorite search engine to find out their purpose.

## Create an image
``sudo docker build -t python-build``

## create a container
``sudo docker run python-build``

# To find a container id, run the following command
``sudo docker container ls -a``
## To kill the container
sudo docker rmi <container_id>

## To find the image id, run-
``sudo docker image ls -a``

## To delete the image run-
``sudo docker rmi <image_id>``
