# Leaf Classification Using Convolutional Neural Networks

**ABSTRACT**:
-----------------------------------------------------------------------------------------

Aim of this project is to understand the nature of Convolutional Neural Networks on vast 
dataset of leaves. Here only 3 classes are taken and using 3 layer architecture with a 
final multi layer perceptron combination, a best accuracy of 33% percent was achieved. 
Since the data is very sparse, messy, of different sizes and with irregularities, the
accuracy did not improve much. This is a very unusual scenario where most possible 
combinations of the network or hyperparameters ended up giving a 33% accuracy only.

**CODE FOLDER**:
------------------------------------------------------------------------------------------

1. CNN.py          :  class file containing CNN architecture, model fitting, evaluation and prediction functions </br>
2. metrics.py      :  class file containing functions to get accuracy, MSE, MAPE, validation-training curves, etc </br>
3. augmentation.py :  class file containing functions to augment images like data reshaping, one-hot-encoding, creating numpy data, etc </br>
4. data_import.py  :  class files containing code to import data from folders and make it in format useable in the code </br>
5. processing.py   :  class files containing functions to scale images, change datatypes, change image aspect ratio, etc </br>
6. leafs.py        :  main file which is the parent file for other class files. This is the main execution point </br>
7. sandbox.py      :  sandbox file is just for testing any feature or code snippet </br>


**DATASET**
------------------------------------------------------------------------------------------
[Leaf Dataset](http://leafsnap.com/dataset/)


**PLOTS FOLDER**:
-------------------------------------------------------------------------------------------


### PART B - changing activations
Activations are changed in this folder, keeping all other hyperparameters constant


### PART C - changing cost
Cost Functions are changed in this folder, keeping all other hyperparameters constant


### PART D - changing epochs
Epochs are changed in this folder, keeping all other hyperparameters constant


### PART E - changing gradients
Gradients are changed in this folder, keeping all other hyperparameters constant


### PART F - changing intialization
Initializations are changed in this folder, keeping all other hyperparameters constant


### PART G - changing hyperparameters
The network architectures, no of layers, epochs and filter sizes were all changed during 
the course of the earlier training


**RESULTS**:
---------------------------------------------------------------------------------------

Convolutional Neural Networks require a lot of data for training, the scarcity of which 
is causing the accuracy to not improve. With various combinations too, the accuracy ends 
up being 33% only which is below average. Data augmentation may help wherein artificial
data can be created and thus can help in increasing the accuracy

**CITATIONS**
---------------------------------------------------------------------------------------

[Tensorflow](https://www.tensorflow.org/)


**CONTRIBUTIONS**
---------------------------------------------------------------------------------------
90% written by me, 10% derived from official documentation
