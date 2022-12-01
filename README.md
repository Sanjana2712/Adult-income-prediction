# Naive-Bayes-Classifier-Adult-income-prediction

Brief summary of the project 

•	Data preprocessing: The adult.csv has within it multiple missing values that are described as “?” instead of the regular NaN. In order to be able to detect null values and handle them, I first replaced all the “?” in the dataset with NaN and then proceeded to handle the null values.

•	Building the classifier: Once the missing values have been handled, I went ahead and wrote the code to calculate prior probabilities, likelihood probabilities and stored them in an organized manner in a Dictionary. I have also added a switch case to let the user choose what method of handling missing values they would prefer.

•	Prediction: Once the functions have been integrated and the model got trained, I created a list named ‘predicted’ to store my model’s predictions on the test dataset. I used ‘0’ to represent ‘<=50K’ and ‘1’ to represent ‘>50K’ output.

•	Accuracy: Once the model has been trained and tested, the accuracy function determines all the accuracy metrics for my model. I accomplished this task by comparing my ‘predicted’ list values with the ‘income’ values in the testset

•	K-Fold validation – I manually created the 10 folds required and ran the model through each of them.

Evaluation measures 

Accuracy - 81.2%
Precision score - 59.6%
Recall score - 73.91%
F1 score - 66%

Instructions to run the program 

1.	Download the Jupyter notebook code file
2.	Download the adult.csv and adult.test and keep it in your local system’s ‘Downloads’ folder
3.	Open the downloaded file in Jupyter and click on Cell → Run all
4.	Enter option “1” or “2” to choose missing value strategy 
5.	Similarly, enter option “1” or “2” to choose Naïve Bayes classifier approach
6.	The model is then tested, and prints the accuracy, precision, recall and F1 score of the classifier
7.	Similarly, the K-fold validation cell outputs the accuracy measures for each fold

