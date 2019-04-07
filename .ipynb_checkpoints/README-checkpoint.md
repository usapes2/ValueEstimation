# ValueEstimation
How do applications automatically predict price of an apartment? This is an example of using machine learning for value estimation. A machine learning model uses information from other properties sold in the area and produces a value estimate for a different house. In this project I build a value estimation system that can produce the value of one's house based on its location and characteristics. Skills that I developed while doing it, can be applied to solve any kind of value estimation problem like :
<br> <b>These awesome applications of Value Estimation </b>
<dl>
  <dt>Fraud Detection</dt>
  <dd>input: details of attempted purchase | output: likelihood purchase is fraud.</dd>
    
  <dt>Loan Quality</dt>
  <dd>input: details of borrower | output: likelihood loan will be paid back</dd>
    
  <dt>Sentiment</dt>
  <dd>input: words in the test of a movie review | output: how positive or negative the review is</dd>
    
  <dt>Diagnosis</dt>
  <dd>input: a medical scan | output: likelihood a certain condition is present</dd>
  
   
    
</dl>
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

# take a look at the environment you created (shows also if packages installed via conda or pip.)
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
Check out this awesome [tutorial](https://youtu.be/a9P7qv4P5LE) to demystify customization in jupyter lab.
What you will find in the Project_code jupyter notebook:


<dl>

  <dt>Building a simple home value estimator</dt>
    <dt>Finding the best weights automatically </dt>
    <dt>
Working with large data sets efficiently </dt>
    <dt> Training a supervised machine learning model</dt>
    <dt>Exploring a home value data set </dt>
    <dt>
Deciding how much data is needed
 </dt>
    <dt> Preparing the features</dt>
    <dt>Training the value estimator </dt>
    <dt>Measuring accuracy with mean absolute error </dt>
    <dt>Improving a system</dt>
    <dt> Using the machine learning model to make predictions </dt>
    <dt> Next steps </dt>
</dl>









