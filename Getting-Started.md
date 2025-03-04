# Getting Started
## Using Python 

1. Set up Anaconda on your computer
You can learn how to get setup using Python [here]([https://www.anaconda.com/docs/main](https://www.anaconda.com/docs/getting-started/getting-started). There are a lot of different ways to use Python, but I use Anaconda locally because it's really user friendly and robust. Then you can use the command line to launch Jupyter notebooks and to install new packages.

2. Install some useful packages
Open a terminal. On macOS and Linux, "Terminal" is an application you can open from the Launchpad or Finder. On Windows, I think you want 
"Command Prompt" which can be found at the Start menu.

  You can now use Anaconda to help you install packages! Try
```
conda install cmocean
```
  for example. cmocean is a package with useful colormaps for plotting oceanographic data. You can use this same syntax to install any package you want, replacing cmocean with the package name. After you run this line, you will probably be given a series of prompts to follow to complete the installation.

3. Launch a Jupyter Notebook
Navigate to the directory you want. For example, you can do

```
cd ~/directory
```
  replacing ~/directory with the path to your directory. Then type

```
jupyter lab
```
  to launch a Jupyter lab window. 

