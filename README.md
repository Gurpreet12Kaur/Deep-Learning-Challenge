# Deep-Learning-Challenge**



**REPORT**:


The purpose of the analysis is to build and optimize a neural network model for binary classification on a dataset related to Alphabet Soup-funded organizations. 
Above is the breakdown of the steps: 

Preprocess Data:
Read data, identify features and targets, drop unnecessary columns.
Encode categorical variables, split data, and scale features.


Build and Train Model:
Design a neural network using TensorFlow/Keras.
Compile, train, and evaluate the model.
Save results to "AlphabetSoupCharity.h5".


Optimize Model:
Create a new notebook.
Repeat preprocessing and adjust for modifications.
Make at least three optimization attempts.
Save optimized results to "AlphabetSoupCharity_Optimisation.h5"


**Data Preprocessing**
Target(s) for the model:
The "successful" column from the "application_df" dataset.

Every other column from the "application_df" dataset.
Variables removed as they are neither targets nor features:
EIN (Employer Identification Number) and NAME columns were dropped.

**Compiling, Training, and Evaluating the Model** 
Model Adjustments:
I experimented with different numbers of neurons and tried adding/removing hidden layers to optimize the model.

Initial Model Configuration:
I initially designed the model with random guesses for neurons, layers, and activation functions, resulting in an accuracy of 72%.

Neurons, Layers, and Activation Functions:
I experimented with different numbers of neurons in hidden layers, trying to strike a balance between complexity and avoiding overfitting. I also explored adding/removing hidden layers to capture patterns while preventing overfitting.

Achieving Target Performance:
Unfortunately, the initial model fell short of the target performance of 75%, achieving an accuracy of 72%.

Steps to Improve Performance:
In attempts to increase model performance, I iteratively adjusted model architecture, activation functions, and hyperparameters. This involved experimenting with various configurations, analyzing data impact, and implementing regularization techniques. Despite initial challenges, these adjustments were crucial in the iterative improvement of the model's accuracy.

