# Data-Science-Environment-Setup


# Step 1: Install Anaconda
https://www.anaconda.com/distribution/#download-section (Download Python 3.7 version) \
If you have Linux, once you download the .sh file, locate it in your directory and run the command chmod u+x to make the file executable. Then, execute it with: ./filename

# Step 2: Create Virtual Environment
conda create -n dsenv python=3.7 anaconda \
conda activate dsenv (example output: (dsenv) adi@vellal-MACH-WX9:~$)


# Step 3: Install TensorFlow, Keras, and Tqdm
conda install -c conda-forge tensorflow \
conda install -c anaconda keras  \
conda install -c conda-forge tqdm \
conda install -c conda-forge matplotlib

# Step 4: Test Python Install
import tensorflow as tf \
import keras \
import numpy \
import matplotlib \
import tqdm 

# Step 5: Jupyter Test and Deactivate Environment
jupyter notebook (type this in terminal with environment activated) \
ctrl + c (press these two keys to get terminal prompt back) \
conda deactivate dsenv (use this to deactivate environment, and then you are free to close your terminal)

# Step 6: Install and Test R and RStudio
Download and Install R: http://archive.linux.duke.edu/cran/ \
Download and Install RStudio: https://www.rstudio.com/products/rstudio/download/#download
Open RStudio application from Desktop to verify installation

# Step 7: Dataiku DSS Environment Setup
If you plan on attending Friday's Dataiku Workshop, please download Dataiku's DSS Free Community Edition here:
https://www.dataiku.com/dss/trynow/free-edition/ \
Select "Install Now" under FREE FOREVER \
Select the OS you would like DSS installed on. \
NOTE: Dataiku comes with Python 2.7 but if you want to import custom Python 3 libraries they can do so here: (https://doc.dataiku.com/dss/latest/code-envs/index.html) \
NOTE: If you want to utilize R with DSS, please use this link to setup: https://doc.dataiku.com/dss/latest/installation/r.html 


# Variational Inference Workshop Python Notebook: 
https://github.com/sergeassaad/VAE_tutorial/blob/master/VAE_sandbox.ipynb

# Additional Resources
Link to Workshop Presentation: \
https://docs.google.com/presentation/d/1o0sPV9MBz45FxlK9IfyheU_JR-1MRop6QDjTLt4DI80/edit#slide=id.g655faf7e89_2_74 

Environment Setup Blog Post: \
https://towardsdatascience.com/installing-keras-tensorflow-using-anaconda-for-machine-learning-44ab28ff39cb
