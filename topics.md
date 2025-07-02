# Topics 

Input Variables / Features

Output Varibles / Targets

Variable Types
- Numericals Variables 
- Categorical Variables
- Binary Variables

Model - Function that maps features to target based on a set of parameters, aimign to capture the underlying relationship between them.

Parameters (weights) - The numerical values that defines the model: dials and knobs. 

Model Training - The process of tuning the weights to improve the overall accuracy

Ex. A simple linear model F(x) = cx , has the parameter c

Loss Function - A function that quantifies the difference, or error, between the predicted and actual target values.

Ex. Mean-squared error, absolute loss, cross-entropy loss

To Minimize the loss function you can differentiate the loss function with respect to the parameter, set the derivative to zero to locate a critical point, varify that it is the minimum with the second derivative test. 

Training data - Data that is used to train parameters and build an accurate model. 

Testing data - The data which is held back to evalute performance.

Risk Function - The function that combines all the loss values across an entire dataset. 

Empirical Risk Function - The average across the loss values. 

**The Modeling method**

1. Identify Input and Output variables 
2. Choose a Model
3. Choose a loss and a risk function 
4. Find a minimizer of the risk