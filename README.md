# Face_Image_Recognition_Model
The model is using the RFMD_part_1 public dataset as the training and testing data sets, And is based on the white paper released by Wuhan University researchers.

# Prerequisites
Python 3
TensorFlow
Jupyter Notebook
You will need to pip3 install the required modules in the notebook/masked-detection-tf.ipynb Jupyter notebook.

# Setup for training
Download the Real world masked face recognition dataset from here. Extract the data and create two directories, train and validation with the following structure:

![Screenshot (55)](https://github.com/Amyydv/Face_Image_Recognition_Model/assets/112614485/b749a31c-f63a-42a7-b130-03c1f6954d19)

I recommend to take ~30% of the individual directories inside the train directory and move them to the validation directory. The notebook assumes this data structure resides in a D: drive. You can change the path in the notebook code.
