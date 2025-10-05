Project Title: Sprint 8/ Supervised Learning

Project Description: This project is mainly about the topic of 'Supervised Learning'. In this project, the main concern is that the Beta Bank (hypothetical company) 
customers are slowly leaving every month. The goal is to create a model to predict whether or not a customer will leave the bank soon. In this project, I decided to 
use the algorithims: Logistic Regression, Decision Tree, Random Forest, XG Boost, and Naive Bayes. The methods that I used to address the class imbalance in the dataset 
are: threshold adjustment, upsampling, and downsampling. 

Task Presented In The Project: Beta Bank customers are leaving: little by little, chipping away every month. 
The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.
We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.
Build a model with the maximum possible F1 score. To pass the project, you need an F1 score of at least 0.59. Check the F1 for the test set.
Additionally, measure the AUC-ROC metric and compare it with the F1.


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

6) Model Training And Predctions Without Addressing Class Imbalance
   
   Model Results:

   1) Logistic Regression Model (Without Addressing Class Imbalance)
   * Logistic Regession Model (Without Addressing Class Imbalance) Training Set Accuracy Score: 0.80
   * Logistic Regession Model (Without Addressing Class Imbalance) Validiation Set Accuracy Score: 0.80
   * Logistic Regession Model (Without Addressing Class Imbalance) F1 Score: 0.30


   2) Decision Tree Classifier Model (Without Addressing Class Imbalance)
   * Decision Tree Classifier Model (Without Addressing Class Imbalance) Training Set Accuracy Score: 0.85
   * Decision Tree Classifier Model (Without Addressing Class Imbalance) Validiation Set Accuracy Score: 0.84
   * Decision Tree Classifier Model (Without Addressing Class Imbalance) F1 Score: 0.48
  



   3) Random Forest Classifier Model (Without Addressing Class Imbalance)
   * Random Forest Classifier Model (Without Addressing Class Imbalance) Training Set Accuracy Score: 0.87
   * Random Forest Classifier Model (Without Addressing Class Imbalance) Validiation Set Accuracy Score: 0.85
   * Random Forest Classifier Model (Without Addressing Class Imbalance) F1 Score: 0.53
  

   4) XG Boost Model (Without Addressing Class Imbalance)
   * XG Boost Model (Without Addressing Class Imbalance) Training Set Accuracy Score: 0.88
   * XG Boost Model (Without Addressing Class Imbalance) Validiation Set Accuracy Score: 0.86
   * XG Boost Model (Without Addressing Class Imbalance) F1 Score: 0.61
  

   5) Naive Bayes Model (Without Addressing Class Imbalance)
   * Naive Bayes Model (Without Addressing Class Imbalance) Training Set Accuracy Score: 0.77
   * Naive Bayes Model (Without Addressing Class Imbalance) Validiation Set Accuracy Score: 0.77
   * Naive Bayes Model (Without Addressing Class Imbalance) F1 Score: 0.08
  
   
   
