# Hyperparameters-in-Neural-Network
Regularization and Dropout technique for overcoming Overfitting (high Variance)
## High Variance
The Bias and Variance trade off are one of the important factors in machine learning and deep learning which determines the performance of the machine learning model.
The high variance occurs due to the Dev/test set that does not performe well or the Error in train set is small as compared to the Error in the Dev/Test set.
## Overfitting
The overfitting is that the  machine learning model captures more noise and performes well on train set but not in the dev/test set.
The high variance problem can be overcome by certain techniques
        1.Training the Neural network with large amount of data
        2.Implementation of Regularization , Data Augmentation , Dropout etc..
        3.Try a new Neural network architecture with more hidden layers.
        
## Regularization
Among the L1 and L2 regularization the "L2 regularization technique " is preferred as the L1 regularization make the weights more parse (more zeros in the matrix).The frobenious form is used in the L2 regularization .The L2 regularization is also called as Weight Decay.
### Note
If the lambda value in L2 regularization becomes larger ,then the weights are reduced as close to zero , then there is chance of getting a linear network.
