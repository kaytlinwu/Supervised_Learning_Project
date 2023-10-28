# machine_learning_project-supervised-learning

## Project Outcomes
Using different supervised learning techniques, the aim is to build a machine learning model using various diagnostic measurements to predict whether or not a patient has diabetes. 

The project includes initial data exploration and data analysis, preprocessing and feature engineering, creating 2 different models and comparing them amongst each other. The models used in this project are SVM (Support Vector Machine) along with Ensemble Modelling using Decision tree, K Nearest Neighbour (KNN), Naive Bayes, and Logistic Regression.

### Duration:
Approximately 3 hours and 20 minutes.

### Project Description:
In this project, supervised learning techniques were applied to the "Diabetes" dataset from the National Institute of Diabetes and Digestive and Kidney Diseases 

The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: Data was imported and cleaned. Columns were analyzed and visualized to see the relationship between variables. Missing values and outliers were handled appropriately, and feature engineering was performed as required.
-	Supervised learning: A machine learning model was created to predict whether a patient has diabetes. Metrics such as recall, accurary, precision, and train/validation error were used. Two models, including one ensemble model and Support Vector Machine, were compared in their performance.

The ultimate goal of the project is to gain insights from the dataset and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked.

## Project Findings:

### SVM vs. Ensemble Model
- Diabetic patients had higher means for each feature which suggests that the higher the value in each parameter, an individual has an increased risk of developing or having Diabetes
- Both SVM and Ensemble Model performanced comparatively.
- Ensemble Model combined different models including decision tree, K Nearest Neighbour, Naive Bayes, and Logistic Regression, the model performed comparatively to each other on both train and test data compared to the SVM Model.
Ensemble Model........................

## Conclusion and Future Considerations
- Further work can be done to reduce the amount of columns that were used in the analysis. In particular, as multicolinearity was suggested between pregnancies and age, those columns could be removed and the models could be re-run
- PCA could be performed to reduce the amount of X variables used
Can try using K-Folds technique to cross-validate

