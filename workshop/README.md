# tensorflow2.0Tutorial

Python=3

## Installation
```
pip install tensorflow==2.0.0-beta0
pip install numpy
pip install matplotlib
pip install pillow

# You can run this in Python to preload the data:
from tensorflow import keras
keras.datasets.mnist.load_data()
keras.applications.VGG16(input_shape=(224,224,3), weights='imagenet',include_top=False)
```


## Usage
This is a brief introduction of tailoring Tensorflow 2.0 for deep learning tasks. Some new features of Tensorflow 2.0 are demonstrated here such as Eagle mode and integrated Keras. 

Some boxes in Eager.ipynb, KerasTraining.ipynb and RawTraining.ipynb are left blanked for you to fill as exercise for workshop. The complete solution is in 'solutins' folder.

The reading order should be as follows.

[Eager.ipynb](./Eager.ipynb) introduces basic operation of tensors and the difference between Eager mode and Graph mode in Tensorflow.

[Data.ipynb](./Data.ipynb) is used for generating dataset for Tensorflow to use. You can use integrated pre-defined dataset or your own data.

[Model.ipynb](./Model.ipynb) introduces three ways in Tensorflow to construct the same model. 

[RawTraining.ipynb](./RawTraining.ipynb) gives an example of training a model from scratch using raw Tensorflow functions.

[KerasTraining.ipynb](./KerasTraining.ipynb) introduces how to perform training using Keras, which is more convenient.

[Transfer_learning.ipynb](./Transfer_learning.ipynb) introduces how to use pre-trained model on your own data to fine-tune a specific model.

