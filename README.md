

# Diabetes Detection Using Machine Learning

Using machine learning we have built a predictive model that can predict whether the patient is diabetes positive or not.". This is also sort of fun to work on a project like this which could be beneficial for the society.
## Technologies Used 

**Language:** Python

**Platform:** Anaconda

**Libraries:** NumPy, Pandas, sklearn


## Methodology
1. Data collection
Collected from kaggle 
https://www.kaggle.com/datasets/mathchi/diabetes-data-set

2. Statistical Measurments

3. Data Standardization

 Data standardization is a data processing workflow that converts the structure of different datasets into one common format of data.
  
  4. Training and Testing of datasets
  (X_train, X_test, Y_train, Y_test = train_test_split(X,Y, test_size = 0.2, stratify=Y, random_state=2)

  5. Modole Building and finding best Accuracy

   
   i) Logistic Regression

   The model builds a regression model to predict the probability that a given data entry belongs to the category numbered as “1”

   ii) Support Vector Machine

   Support Vector Machine (SVM) is a relatively simple Supervised Machine Learning Algorithm used for classification and/or regression. 

   iii) KNN

   The supervised learning domain and finds intense application in pattern recognition, data mining and intrusion detection.

   iv) The Random forest classifier
   
   The Random forest classifier creates a set of decision trees from a randomly selected subset of the training set. It is basically a set of decision trees (DT) from a randomly selected subset of the training set and then It collects the votes from different decision trees to decide the final prediction.

   v) DecisionTreeClassifier

   A decision tree is a flowchart-like tree structure where an internal node represents feature(or attribute), the branch represents a decision rule, and each leaf node represents the outcome.






## Deployment

To deploy this project used steamlit

Anconda enviroment used in deployment

```bash
  streamlit run "filename"
```

