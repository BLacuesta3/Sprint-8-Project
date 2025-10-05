Project Title: Sprint 8/ Supervised Learning

Project Description: This project is mainly about the topic of 'Supervised Learning'. In this project, the main concern is that the Beta Bank (hypothetical company) 
customers are slowly leaving every month. The goal is to create a model to predict whether or not a customer will leave the bank soon. In this project, I decided to 
use the algorithims: Logistic Regression, Decision Tree, Random Forest, XG Boost, and Naive Bayes. The methods that I used to address the class imbalance in the dataset 
are: threshold adjustment, upsampling, and downsampling. This project also includes the use of an ROC Curve for evaluating the performance of the final model.

Task Presented In The Project: Beta Bank customers are leaving: little by little, chipping away every month. 
The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.
We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.
Build a model with the maximum possible F1 score. To pass the project, you need an F1 score of at least 0.59. Check the F1 for the test set.
Additionally, measure the AUC-ROC metric and compare it with the F1.

Project DataFrame: 'Churn.csv'

Project Libraries Used:

* pandas

* sklearn.model_selection (functions: train_test_split(), RandomizedSearchCV())

* sklearn.linear_model (function: LogisticRegression())

* sklearn.model_selection (funtion: GridSearchCV())

* sklearn.metrics (functions: confusion_matrix(), f1_score(), precision_score(), recall_score(), classification_report(), roc_auc_score(), roc_curve())

* sklearn.tree (function: DecisionTreeClassifier())

* matplotlib.pyplot

* sklearn.utils (function: shuffle())

* sklearn.ensemble (function:RandomForestClassifier())

* numpy

* xgboost 

* sklearn.naive_bayes (function: GaussianNB())

Models Included In The Project:

* Logistic Regression

* Decision Tree Classifier

* Random Forest Classifier

* XG Boost

* Naive Bayes


Project Methodology:

1) Importing The Necessary Libraries

2) Data Cleaning/ Data Preprocessing

3) Feature Encoding (One-hot Encoding Method Used For Encoding Categorical Features)

4) Data Splitting

5) Expolartory Data Anaysis (EDA) For Displaying Class Imbalance

6) Model Training And Predictions Without Addressing Class Imbalance

7) Model Training And Predictions With Threshold Adjustment

8) Model Training And Predictions With Upsampling

9) Model Training And Predictions With Downsampling

10) Choosing Final Model 

    Final Model Chosen:

     * XG Boost Model (With Downsampling Applied)

     * XG Boost Model (With Downsampling Applied) Training Set Accuracy Score: 0.83
   
     * XG Boost Model (With Downsampling Applied) Validation Set Accuracy Score: 0.82
     
     * XG Boost Model (With Downsampling Applied) Test Set Accuracy Score: 0.82
   
     * XG Boost Model (With Downsampling Applied) F1 Score: 0.63
   
     * XG Boost Model (With Downsaampling Applied) Confusion Matrix Result:

       [[1228,  213]
       
       [ 104,  273]]
   
     * Final Model Conclusion:

       Out of all the other models, the XG Boost Model which used the downsampling technique generated the best F1 score. For this task, I concluded that
       downsampling was more effictive and generated better F1 scores than: leaving the class imbalance as is, adjusting the threhold, or upsampling. The class imbalance of:
       appoximately 80:20, with the 0 class being the majority class needed to be addressed in order to generate the most accurate results from a model. The Downsampled XG Boost
       model had the highest F1 score of all the other models and also had a good AUC-ROC score and a good area under the curve according to ROC Curve chart.
 
