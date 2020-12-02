Steps to build and run the image using the dockerfile

step 1: Make sure you’re in the directory

step 2: run the following command

docker build --tag myimage .

docker images

docker run -it --rm myimage  /bin/bash