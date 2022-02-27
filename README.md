# Neural Network Charity Analysis

## Overview 
The purpose of this project is to create a deep learning neural network to help Alphabet Soup determine which donation recipients are likely to use donation money effectively and which hare not. In the past, some donation recipients have received donations and not utilized the money as expected or disappeared after receiving the money. Alphabet Soup would like to be able to more accurately predict which organizations are worth donating to. 

## Results

#### Data Preprocessing
 * The 'Is_Successful' column is the target for this model as it determines if the donations are effectively used. 
 * The following variables are the features of this model: application_type, affiliation, classification, use_case, organization, status, income_amt, special_considerations, ask_amt. 
 * The columns 'EIN' and 'Name' were dropped as there were neither targets nor features. 

#### Compiling, Training, and Evaluating the Model 
 * There were three hidden layers used for this neural network model. There were 120, 50 and 30 neurons in the first, second and third layers respectively. The Sigmoid and ReLU activations functions were both used. 
 * Target performance of 75% accuracy was not achieved. The highest accuracy achieved was 73.67% in the third optimization model. 

![Accuracy](https://user-images.githubusercontent.com/91712554/155863771-be624b91-030b-40cb-8f12-3b152efb5862.png)


 * Attempts to optimize the model included adding additional hidden layers. Models with both three and four hidden layers were tried. In addition, the number of neurons in each layer were increased, which resulted in the most accurate model. Lastly there were changes made to the activation function, trying both Sigmoid and ReLU. However, performance of 75% was not achieved by any of these models. 

## Summary 
Ultimately the 75% target was not achieved, even after optimization attempts. Additional optimization recommendations include adjusting the number of neurons for each hidden layer and the corresponding activation functions. 
