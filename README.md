# Neural-Network-from-scatch
I have created a Deep L-layered Neural network from scratch and Tested on Cat or Non-Cat recognizer.
This is basically a process which is vectorised.
Flow of the code file:
1. Starting from initializing paramters for L layers but i have tested it for 2 layer initially.
2. Then performing linear forwared function which is Z = W*A + b
3. Then a linear activation funtion, here for L-1 layers we have defined ReLu as a activation function but for last 
   layer activation function is Sigmoid.And even for ReLu and Sigmoid functions are defined.
4. Then lastly defining L-Layered netwrk for forward propogation where output is A_L , this completes our Forward 
   Propogation.
5. We then move on creating a cost function which is well defined for Logistic regression as
   J = - y*log(A_L) - (1-y)log(1-A_L)
6. Then we move on to perform Back propogation for updating our Model parameters.
7. Finally a L-Layered mdeep neural network model is defined with forward and backward propogation and tested on 
   h5py data-set which has labelled images if it is cat or non-cat.
