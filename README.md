# Analysis of all Deep Learning model and their performance over MNIST dataset


Hyperparameters we will be dealing with each Classification Algorithm:
1. Learning Rate Dynamics
2. Momentum Dynamics
3. Learning Rate Decay
4. Drop Learning Rate On Plateau
5. Adaptive Learning Rates



The Learning rate we chose in these experiments are as follows:
1. 1E-0
2. 1E-1
3. 1E-2
4. 1E-3
5. 1E-4
6. 1E-57. 1E-6
8. 1E-7
These learning rates are in logarithmic scale and ranges from 0-1.



We use the following momentum values :
1. 0.0
2. 0.5
3. 0.9
4. 0.99
This momentum parameter will thus enable us to check the acceleration in training time and
accuracy.




In this experiment we are using the following decay rates:
1. 1E-1
2. 1E-2
3. 1E-3
4. 1E-4
We then compare the performance of the model and the accuracy over each decay rate.



The following patience and factors are chosen for this experiment :
1. 2
2. 4
3. 8
4. 10
And factor is set to 0.1
This will help us conclude the learning rate performance and the time for convergence and the
accuracy.




Adaptive Learning Rate
We know the learning rate and the Decay rate are very critical and hard to implement. And there
is no hard and fast rule to get the best values. In order to deal with this, there are previously
best known algorithms for the learning rate, they are as follows:
1. Adaptive Gradient Algorithm (AdaGrad)
2. Root Mean Square Propagation (RMSprop)
3. Adaptive Moment Estimation (Adam)



-----------------------------------------------------------------------------------------------------------------------------

Model Execution time(s) Tess Loss Tess Accuracy
CNN      257.5474        0.3140     1.0000
RNN      537.8466        1.2129     0.5368
MLP      114.1725        0.0400     0.9800
Siamese  18.5591         0.0084     0.9961
Network   0.9961

Knowledge 11.7357         0.0239    0.9931
Transfer 
Model 
