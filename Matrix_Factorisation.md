# Matrix Factorisation

- Often used in recommendation systems
- Helps to reduce the number of parameters needed to estimate preferences
- Does so by taking information from preference matrix more efficiently
- E.g. Users x Movies matrix becomes
    - Users x features matrix AND
    - Movies x features matrix 
- Corresponding dot products of row and column then yield rating value. 

Requires:

 - User ID's
 - Thing being reviewed and its constituent components (features). E.g. Diehard is 3 x Action feature and 1 x festive feature. 
 - User preferences i.e. how much weight user gives to feature. 
 
 
 Method:
 
 - Use gradient descent to identify factor matrices. 
 - Initialise with random values
 - Number of features wanted is hyperparameter
 - Define error function - often sum of squared error. 
 - Take derivative of error function and move in opposite for gradient descent. 
 
 
 Notes:
 - Initial matrices are often sparse. 
