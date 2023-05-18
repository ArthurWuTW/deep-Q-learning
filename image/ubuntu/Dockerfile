# ubuntu binoic 18.04
FROM fullaxx/ubuntu-desktop:bionic 

RUN apt-get update -y
RUN apt-get install init vim git net-tools -y

RUN apt-get install -y python3 python3-pip

RUN apt-get install libjpeg-dev zlib1g-dev python3-tk -y
RUN pip3 install pygame torch torchvision IPython matplotlib