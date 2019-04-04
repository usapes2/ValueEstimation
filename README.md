# ValueEstimation
How do applications automatically predict price of an apartment? This is an example of using machine learning for value estimation. A machine learning model uses information from other properties sold in the area and produces a value estimate for a different house. In this project I build a value estimation system that can produce the value of one's house based on its location and characteristics. Skills that I developed while doing it, can be applied to solve any kind of value estimation problem with ML approach.

### Prerequisites

Python 3, pandas, numpy, jupyter lab and whatnot ...

Download Anaconda for your platform at https://www.anaconda.com/download
Conda is a package manager and you can manage [virtual environment](https://docs.python.org/3/library/venv.html) and install packages.
<br> <b>Note:  </b>
<dl>
  <dt>conda install</dt>
  <dd>installs any software package.</dd>

  <dt>pip install</dt>
  <dd>installs python packages only and it’s the defacto python package manager</dd>
</dl>

To start with conda use these commands ( open [terminal](https://macpaw.com/how-to/use-terminal-on-mac) on mac or [terminal](https://askubuntu.com/questions/183775/how-do-i-open-a-terminal) on ubuntu or [command prompt](https://www.digitalcitizen.life/7-ways-launch-command-prompt-windows-7-windows-8) on windows ( click win + R button type in cmd and press Enter)

```
# First things first run these two
conda upgrade conda
conda upgrade --all

# create a new environment with conda with the name coffee
conda create -n coffee

# activate the environment you created
conda activate coffee

# take a look at the environment you created (to see the list of packages installed and whether they are installed with conda or pip.)
conda info
conda list 

# install a package manager PIP with conda and verify it's installed
conda install pip
conda list

# instal everything else with pip
pip install numpy
pip install pandas
pip install matplotlib
pip install -U scikit-learn
pip install jupyterlab

# take a look at the list of environments you currently have
conda info -e

# if needed remove an environment use this one
conda env remove --name [my-env-name]

# to start jupyter lab
jupyter lab

```


