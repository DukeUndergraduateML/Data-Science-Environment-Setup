# Data-Science-Environment-Setup


# Step 1: Install Anaconda
https://www.anaconda.com/distribution/#download-section (Download Python 3.7 version) \
If you have Linux, once you download the .sh file, locate it in your directory and run the command chmod u+x to make the file executable. Then, execute it with: ./filename

# Step 2: Create Virtual Environment
conda create -n dsenv python=3.7 anaconda \
conda activate dsenv → (dsenv) adi@vellal-MACH-WX9:~$ 

# Step 3: Install TensorFlow, Keras, and Tqdm
conda install -c conda-forge tensorflow \
conda install -c anaconda keras  \
conda install -c conda-forge tqdm 

# Step 4: Test Python Install
import tensorflow as tf \
import keras \
import numpy \
import matplotlib \
import tqdm 

# Step 5: Install and Test R and RStudio
Download and Install R: http://archive.linux.duke.edu/cran/ \
Download and Install RStudio: https://www.rstudio.com/products/rstudio/download/#download

Open RStudio application from Desktop to verify installation



# Additional Resources
Link to Workshop Presentation: \
https://docs.google.com/presentation/d/1o0sPV9MBz45FxlK9IfyheU_JR-1MRop6QDjTLt4DI80/edit#slide=id.g655faf7e89_2_74 

Environment Setup Blog Post: \
https://towardsdatascience.com/installing-keras-tensorflow-using-anaconda-for-machine-learning-44ab28ff39cb
