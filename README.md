# MNIST digit reconization
Building a digit recognition pipeline for the MNIST data set of written digits. Part of the kaggle datasets.

### Installation

Complete python dependancies are found in > requirements.txt
Code for the analysis is found in > notebooks/


### Data structure
Data is stored in a file system as detailed below:

> data/raw
> data/interim

Raw data is seperated in training and testing csv files found in the raw dir.

### Building the model
**Data preperation**

Data was prepared and normalized in **MNIST_digits_dataprep.ipynb**. Data was out put to data/interim/

**tSNE**

tSNE model was applied to a subset of the data in **tSNE_cluster_MNISTdigits.ipynb** for testing whether clustering could be applied post tSNE.

**Deep learning network**

A deep learning network was set up with TensorFlow, through Keras.
