#GALAXY_ML

A image classification algorithm built for classifying galaxies based on different parameters using neural nets.
This project is a part of galaxy zoo challenge on kaggle. This was a  crowd sourced project to better undestand galaxies just from the images .

Dataset : The dataset consisted of two parts 1) Csv sheet of Target Labels
                                                a) There are different column corresponding to Each of the features of galaxy.
                                             2) Folder containing 75k Images.
                                             
Architechture : A neural net of Dimension [ 20 , 7 , 5 , 5 ,1 ]  
                
Initialization : Random initialization , Adam Initialization [Default] , Momentum Initialization.

Sampling : Mini-batch [128 , Default] , Batch Gradient .

Activation Functions : ReLu for 1,L-1 layers , Sigmoid for last layer L.

Regularization : Drop-Out Regularization.



Benchmarks : Training avg : 98 %
             Test accu : 74 %
             
 Result : Overfitting . Still in Progress.



