# Jupyter And It's Moons - An Introduction to Jupyter and its Ecosystem

## Presented by: Shreyas Cholia, Matt Henderson, Oliver Evans
## Gateways 2017, Ann Arbor MI


## Installation 

We will use the anaconda stack to simplify the installation process. You will need to download Anaconda (Python 3) https://www.anaconda.com/download/ to get started. 

Install instructions for your platform can be found here:
https://docs.anaconda.com/anaconda/install/

Windows users should install anaconda using the default options in the installer.

Optionally you can also do this tutorial via docker. If you go this route, we'll assume you already have [[Docker][https://www.docker.com/get-docker]] installed and are familiar with basic Docker concepts since this is not meant to be a Docker tutorial.


## Running (Linux/OS X)

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

docker run -p 127.0.0.1:8000:8000 -p 127.0.0.1:8888:8888 -v`pwd`:/opt/Jupyter-and-its-moons -i -t continuumio/anaconda3 jupyter notebook --notebook-dir=/opt/Jupyter-and-its-moons --ip='*' --allow-root
```

This should start jupyter and you will see something that looks like this:
```
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=c23aafa8269872fb603b5ea6c62363f315139133850678e3
```

Go to the above URL

Welcome to Jupyter!

## Running (Windows)

Download git for windows:
https://git-scm.com/download/win

Run the installer that was downloaded:
Git-2.14.2.3-64-bit.exe

On the last screen, select "Launch Git Bash", then click "Finish".

Inside the terminal:
```
git clone https://github.com/Jupyter-Kale/Jupyter-and-its-moons.git
```

Launch Jupyter Notebook from your start menu or apps.  This will open the interface in your default browser in your user home.
You can navigate to where you checked out the "Jupyter-and-its-moons" repository above and follow along.

