# Analysis of Optimum Gesture Recognition of hand for prosthetic optimisation.


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
this is a neural netowrk designs to recognise with varying accuracy a set of hand gestures for imporving the motor responses of a prosthetic hard. 
it was gathered using 8 sensors on the forearm to collect 64 features that are catergorised into 4 catergories, rock, paper, scissors, and ok sign. 
the CNN, using a varying amount of layers, uses the coordinate data to correcting identify each gesture, with a 96% accuracy rate. 
though it can have adverse accuracy when coming across other gestures or forearms of different lenghts, 
it provides a foundational tool for hand-recognition algorithms to be easily applied to porsthetic limbs

## DATA
source: https://www.kaggle.com/datasets/kyr7plus/emg-4/data

Composed of 64 features, representing 8 readings from the forearm sensors on the skin to measure electrical pulse activity
4 classes fo gestures: rock, papar, scissors, and Ok.

unfortunetly, data is only from the right forearm and can only recognise 4 gestures


## MODEL 
CNN with multiple layers to reformat the 2d matrices to 1 vectors to test the accuracy of the model. 
Composed of a input layer to reshape the data, 
convolution data to determine the kernal size
flatten layer for 1D conversion
dense layer for 128 neurons
output layer for 4 neurons

## HYPERPARAMETER OPTIMSATION
alteration of accuracy metrics to determine overall accuracy of either gesture detection, or comparisons between each gesture

## RESULTS
The highest accuracy achieved is approximately 96%.
data from the 4 gestures is accurate enough tol be utilised further for finetuning prosthetic motor movement

You can include images of plots using the code below:
![download](https://github.com/NAlfar/Portfolio_project/assets/171687794/99fd4d6b-3c16-4ffb-8835-85e10f927ec8)


