# machine_learning_project-supervised-learning

## Project Outcomes
Using different supervised learning techniques, the aim is to build a machine learning model using various diagnostic measurements to predict whether or not a patient has diabetes. 

The project includes initial data exploration and data analysis, preprocessing and feature engineering, creating 2 different models, and comparing them against each other. The models used in this project are SVM (Support Vector Machine) along with Ensemble Modelling using Decision tree, K Nearest Neighbour (KNN), Naive Bayes, and Logistic Regression.

### Duration:
Approximately 3 hours and 20 minutes.

### Project Description:
In this project, supervised learning techniques were applied to the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases 

The project involves the following tasks:

-	Exploratory data analysis and pre-processing: Data was imported and cleaned. Columns were analyzed and visualized to determine the relationship between variables. Missing values and outliers were handled appropriately, and feature engineering was performed as required.
-	Supervised learning: A machine learning model was created to predict whether or not a patient has diabetes. Metrics such as recall, accurary, precision, and train/validation error were used to meaure a model's performance. Two models, including one ensemble model and Support Vector Machine, were compared.

The ultimate goal of the project is to gain insights from the dataset and to communicate these insights to stakeholders using appropriate visualizations and metrics in order to make informed decisions.

## Project Findings:

### SVM vs. Ensemble Model
#### SVM
- The model had a precision value of 0.74, an accuracy value of 0.80 and a recall value of 0.596. 
    - Precision: the model is able to identify diabetic patients 74% correctly.  
    - Accuracy: 80% of the predicted data was clasified correctly using the model.
    - Recall: 59.6% of positives were correctly identified as positive. 
- Though the precision and accuracy of the SVM model was quite high, in comparison, the recall was quite low. The low recall value suggests that the model fails to identify a large portion of true positives. 

#### Ensemble Model
- The ensemble model had following output:
    - Ensemble Model:  Training error: 0.21;  Validation error: 0.21
    - Decision tree: Train_error: 0.181; Validation error: 0.219
    - KNN: Train_error: 0.214; Validation error: 0.245
    - Naive Bayes: Train_error: 0.234; Validation error: 0.234
    - Logistic Regression: Train_error: 0.240; Validation error: 0.203

- The values for the train and validation error were similar, which suggests the models are not over or underfitting data. 
- For the Ensemble model and Naive Bayes, the train and validation error were the same value. This means the model performed the same on training dataset and the validation dataset.
- The Decision tree model had the lowest training error; however, the validation error was higher. 
- The KNN model had a lower training error than the validation error. The model performed worse on the validation data. 
- The Logistic Regression model was the only model where the model performed better on validation data than on training data. Meaning that on unseen data, the model performed better with less error. 

## Future Considerations
- PCA or dimension reduction techniques could be performed to reduce the amount of X variables used 
- Can try using K-Folds technique to cross-validate
- Can try different models to see if the better is better fit

 ## Conclusion
- Diabetic patients generally had higher mean values than non diabetic patients in the features that were measured in this dataset. 
- Although the SVM model had a high precision and accuracy score, the recall score was found to be significantly lower. This suggests that this model is not able to accurately identify true positives.
- The Ensemble Model combined different models including decision tree, K Nearest Neighbour, Naive Bayes, and Logistic Regression. This model outperformed the SVM model. 
- The Ensemble Model had a good output with low train and validation errors (both values ~0.2) without over or underfitting data. With low train and validation error, it means that the model is able to classify the data well. 

