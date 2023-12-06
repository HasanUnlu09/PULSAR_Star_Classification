# PULSAR Star Classification

## Project Description
In this project, classifying a PULSAR star is the main goal of the project. In order to obtain data, **UC Irvine Machine Learning Repository** is used. If you would like to see content of the dataset, you can check out the dataset in the **HTRU_2.csv** file or you can visit the [**UCI ML Repository - HTRU2**](https://archive.ics.uci.edu/dataset/372/htru2) webpage. In order to accomplish classification operation, following Classification ML Algorithms are used, **Logistic Regression, Decision Tree Classifier, Support Vector Machines(SVM) Classifier, Naive Bayes Classifier,  K-Nearest Neighbors(KNN) Classifier, Random Forest Classifier, AdaBoost, GradientBoosting** and **eXtremeGradientBoosting**. These ML Algorithms are evaluated by using **F1-Score**, **ROC Curve** and **AUC-Score** metrics. F1-Score is used and using Accuracy metric is avoided because of imbalance dataset. As a result of these algorithms, best performed model is the *eXtremeGradientBoosting* algorithm with **0.896774 F1 score**. Also, it has the **widest AUC** among all applied models with **0.929800** value. It should be mentioned that, Data Science Project LifeCycle is followed on this project to effectively simulate business level project handling as it can be seen from the following image. Therefore, project is formed in to 7 steps with the proceduralized contents and the step/file names are as follow; **1. Business_Understanding**, **2. Data_Mining**, **3. Data_Cleaning**, **4. Data_Exploration_(EDA)**, **5. Feature_Engineering**, **6. Predictive_Modelling_&_Evaluation** and **7. Data_Visualization**.

![Data_Science_LifeCycle](https://github.com/HasanUnlu09/PULSAR_Star_Classification/assets/133260754/3bc1fdb8-90d7-4352-b404-d6ea489f0306)

## Install/Run
Each Data Science LifeCycle steps in Jupyter Notebook files can be runned one by one on your computer to see the results. If you want more generalized and compact file you can download and run **PULSAR_Star_Classification.ipynb** Jupyter Notebook. 

## Project Outcomes

All of the confusion matrix result for each model can be seen from the below image
![1  Confusion_Matrices](https://github.com/HasanUnlu09/PULSAR_Star_Classification/assets/133260754/aa19df9e-4634-4b80-a96c-455e70ff0e16)

In the below image it can be seen that how well the model performed by considering F1-Score
![2  F1-Scores](https://github.com/HasanUnlu09/PULSAR_Star_Classification/assets/133260754/14e100f3-fa82-49e3-938c-e871cfb07ada)

ROC(Receiver Operator Characteristic) Curves for all models are shown in the below image
![3  ROC_Curves](https://github.com/HasanUnlu09/PULSAR_Star_Classification/assets/133260754/89ae6628-44ef-4604-93c2-900848f42084)

AUC(Area Under Curve) Scores is represented in the below bar plot to compare models with each others
![4  AUC_Scores](https://github.com/HasanUnlu09/PULSAR_Star_Classification/assets/133260754/cbea7be5-199e-43c3-9d22-bef0ecb94062)

The Dataset Citation  
Lyon,Robert. (2017). HTRU2. UCI Machine Learning Repository. https://doi.org/10.24432/C5DK6R.

!!! If you would like to reach me out about this project you can use following e-mail address; hasan.09.unlu@gmail.com
