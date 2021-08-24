Code for BankNote Authentication (Classification problem)

Dataset Info:-
 Features: Variance of Wavelet Transformed Image (VoWTI)
          Skewness of Wavelet Transformed Image (SoWTI)
          Kurtosis of Wavelet Transformed Image (CoWTI)
          Entropy of Image (EoI)
 Class - 0 -- Fake Note
         - 1 -- Original Note

Model Used:-

1. Using K-NN 
   The K-nearest neibhbour algorithm was applied to this dataset.
   Fistly we normalize the dataset after importing it and then choose even no. of samples from both the classes.
   We separate the above set into 80:20 ratio and then use the test data set to find the minimum distance from the training datatset and assign the class from the most    frequently occuring in K-nearest.  
   Then we calculate the accuracy by comparing the predicted(hypothesis) class and the actual class.

2. Using Logistic Regression
   The Logistic regression algorithm was applied to this dataset.
   Fistly we normalize the dataset after importing it and then choose even no. of samples from both the classes.
   We separate the above set into 80:20 ratio and then using the training set we train the model and we try to the cost function by finding the optimum weight.
   This is done using Stochastic Gradient Descent algorithm and iterating it several no. of times till it get converged or we find min. value of cost func.
   Then using this weight vector we calculate our hypothesis for test data and match with the actual output and calculate the accuracy of the model.
  
