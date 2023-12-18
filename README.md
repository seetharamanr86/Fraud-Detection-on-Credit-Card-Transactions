# Fraud-Detection-on-Credit-Card-Transactions
This repo contains ML model and analysis used for detecting fraud in credit card transactions using machine learning models.

**Seetharaman Rajendran**

#### Executive summary
Per Nilson's report in 2022, payments industry in the United States is expected to incur $165 billion loss in the next 10 yrs due to fraudulent use of credit cards.
It can be largely reduced by building a more robust fraud detection system using machine learning models. 
This work aims to use some sample dataset, analyze the data, build few ML models, compare and suggest a best model suitable for this use case.

#### Rationale
There are a couple primary beneficiaries. The finance organizations (credit card companies, insurance companies) directly deal with this loss.
Innocent customers are impacted as well, where they lose their hard earned money.

#### Research Question
Identify and prevent fraud transactions in credit cards in realtime and thereby protect customers from losing money and help finance companies well serve their customers better.
Our focus will be on coming up with a machine learning model that can predict the fraud transaction accurately.

#### Data Sources
Will be using the dataset named 'Credit Card Transactions Fraud Detection Dataset' in Kaggle.
This is a simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020. 
It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.

#### Methodology
We will go through the following stages - Problem Identification, Dataset Selection, Data Cleaning, Exploratory Analysis, Statistical Analysis, Build Machine Learning Models, Evaluate/Compare Models.
We will use various classification techniques to arrive at a best model for fraud detection.

#### Results
Results based on the research are as follows.

LR Accuracy: 82.135% LR Precision: 86.269% LR Recall: 76.430% LR F1_Score: 81.052%
KNN Accuracy: 91.631% KNN Precision: 89.298% KNN Recall: 94.598% KNN F1_Score: 91.872%
SVM Accuracy: 96.160% SVM Precision: 97.059% SVM Recall: 95.205% SVM F1_Score: 96.123%

After evaluating the models, gives an idea how the classification models are performing.

We have used the hyper parameters to tune to get the best model possible in each category, then compared various scores with one another.

SVM model provides a better accuracy compared to other models.
SVM model provides a better precision compared to other models.
SVM model provides a better recall compared to other models.
SVM model provides a better f1 score compared to other models.

KNN stands next to SVM in terms of scores, from above evaluation.

#### Next steps
Find out the deployment strategry to use the model for fraud detection in real time.

The key for success would be to plug this model in a real time environment and make it improve by itself, learning from training using real time data.

This model alone cannot solve the larger problem of mitigating fraud but this can help identify the fraud transaction and together with other well management processes, this can contribute towards fraud detection and prevention overall. 

#### Outline of project
Notebook: capstone - [credit card fraud analysis.ipynb](https://github.com/seetharamanr86/Fraud-Detection-on-Credit-Card-Transactions/blob/main/capstone%20-%20credit%20card%20fraud%20analysis.ipynb)

##### Contact and Further Information
Seetharaman Rajendran
seetharaman.rajendran.86@gmail.com
