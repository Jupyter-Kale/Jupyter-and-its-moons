# Jupyter And It's Moons - An Introduction to Jupyter and its Ecosystem

## Presented by: Shreyas Cholia, Matt Henderson, Oliver Evans
## Gateways 2017, Ann Arbor MI


## Installation 

We will use the anaconda stack to simplify the installation process. You will need to download Anaconda (Python 3) https://www.anaconda.com/download/ to get started. 

Install instructions for your platform can be found here:
https://docs.anaconda.com/anaconda/install/

Optionally you can also do this tutorial via docker. If you go this route, we'll assume you already have [[Docker][https://www.docker.com/get-docker]] installed and are familiar with basic Docker concepts since this is not meant to be a Docker tutorial.


## Running

Anaconda:
```
source /path/to/anaconda3/bin/activate
git clone https://github.com/Jupyter-Kale/Jupyter-and-its-moons.git

cd Jupyter-and-its-moons
jupyter notebook
```

Docker:
```
git clone https://github.com/Jupyter-Kale/Jupyter-and-its-moons.git

cd Jupyter-and-its-moons

docker run -p 8888:8888 -v`pwd`:/opt/Jupyter-and-its-moons -i -t continuumio/anaconda3 jupyter notebook --notebook-dir=/opt/Jupyter-and-its-moons --ip='*' --allow-root
```

This should start jupyter and you will see something that looks like this:
```
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=c23aafa8269872fb603b5ea6c62363f315139133850678e3
```

Go to the above URL

Welcome to Jupyter!

