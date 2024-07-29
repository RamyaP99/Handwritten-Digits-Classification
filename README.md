# Handwritten-Digits-Classification
Developing a model using SVM(Support Vector Machine) that can correctly identify the handwritten digits based on pixel values.

For MNIST data I have used SVM algorithm (I choose SVC).

SVC has linear and Non linear models (like RBF kernel). I have build these models with default hyper parameters to check the accuracies.

Steps:- 
* Lode the Data
* Check is there any missing values (null values) in the dataset.
* Train and Test the Data.
* Scaling data by using standardscaler.
* Model building.
  
I checked the accuracies for both linear and non linear (rbf) models.

* LINEAR MODEL
  > Kernel = “linear”

  > Accuracy Score is “91.94%”

* NON LINEAR MODEL
   > Kernel = “rbf”
   
   > Accuracy Score is “95.77%”

--> Conclusion

SVC with non linear model (kernel=”rbf”) performed well with an accuracy of “96%” approx than the linear model (kernel=”linear”) with an accuracy of “92%”.

Non linear model takes more time than linear model to run.

So, I prefer to choose Non linear model (kernel=”rbf”) as it performs well with a high accuracy.

