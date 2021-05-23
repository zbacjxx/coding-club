# Coding Club - Getting started

## Install Miniconda3
First of all we need to get and install Miniconda3.  This can be downloaded 

* Windows link [here](https://repo.anaconda.com/miniconda/Miniconda3-py39_4.9.2-Windows-x86_64.exe)
* Mac link [here](https://repo.anaconda.com/miniconda/Miniconda3-py39_4.9.2-MacOSX-x86_64.pkg)

Once downloaded install using all the defaults, in windows tick "add to path" if offered!

## Create environment - ONE OFF SETUP
First we need to create a new environment which will contain all of the dependencies to run Jupyter Lab Notebooks:

In windows start an Anaconda Shell, and on a mac start a Terminal

    conda create -y -n jupyter-lab jupyterlab

Note: We can create many environments, but for now we only need the one!
## Activate environment
Once the environment is created, you need to "activate" the environment to point to the version of Python with Jupter Lab installed:

    conda activate jupyter-lab

## Create a drive for working in - ONE OFF SETUP
We need to create a working directory that we can save all of our work in:

Mac:

    mkdir -p ~/workspace/coding-club


Windows

    mkdir %USERPROFILE%\workspace\coding-club
## Now change directory to that location
Before we start the Jupyter lab server we need to make sure we are in the right directory:

Mac:

    cd ~/workspace/coding-club

Windows:

    cd %USERPROFILE%\workspace\coding-club
## Now start a lab session
We are now good to go, run the following command to fire up Jupyter Lab:

    jupyter lab

