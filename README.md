# neural-network-challenge-1

This is a LLM that is being used to predict student loan repayment. 
A csv file containing data on previous student loan recipients will be used to 
determine if an applicant will or will not repay his/her student loan.

A starter code is provided "student_loans_with_deep_learning.ipynb"
The data is read into a Pandas DataFrame.
The data is cleaned, then scaled with scikit-learn's StandardScaler().

The target is the "credit_ranking" column. 

The model is compiled and evaluated using a TensorFlow neural network with the relu activation function. 
Compiled and fit with the binary_crossentropy loss function,
the adam optimizer, and the accuracy evaluation metric.

Use 50 to 100 epochs.

Save and export the model to the student_loans.keras file.

Predict loan repayment success by reloading the saved model.
Save the predictions to a DataFrame and round the predictions to binary values.

Answer a few questions.



