# Graph-classification-using-ML
Graph classification from symbolic time series data using Machine learning

## Required packages
-'Keras 2.4.0'

-'Tensorflow 2.4.1'

## Overview

'main.ipynb' Code to train the network and plot the results.

'dataset_example' Example data of ER, SF, and SW networks for model training.

#'data_generation_code' <--- We need to supplement this folder and code.

## Usage

Open main.ipynb in the Jupiter notebook environment.

The first kernel loads the data the model needs to train. 
- In the case of 2-class classification such as ER and SF classification, the commented out part at the bottom of the kernel must be activated. 

In the second kernel, the model trains the data from the first kernel.
- Set 'length_list' and 'node_list' to train the model by changing the node and time-series length.


Check the model performance in the third kernel.
