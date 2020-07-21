# project-2

Project name:Credit Card Fraud Detection

Abstract:The usage of credit cards for online and regular purchases is exponentially increasing and so is the fraud related with it. A large number of fraud transactions are made every day. Various modern techniques like Data Mining, Genetic Programming, etc. are used in detecting fraudulent transactions. This project uses  algorithm which comprises of techniques for finding optimal solution for the problem and implicitly generating the result of the fraudulent transaction. The main aim is to detect the fraudulent transaction.

Process:-

1.Collecting Data: - Took data set from Kaggle.

2.Analyzing Data: - Explore our data as much as possible like check that  Due to some confidentiality issues, the original features are replaced with V1, V2, … V28 columns which are the result of PCA transformation applied to the original ones. The only features which have not been transformed with PCA are ‘Time’ and ‘Amount’. Feature ‘Class’ is the response variable

3.Data wrangling: - Filter the columns to remove data we do not want or which is not useful in data set .

4.Train & Test: - Build the model using train data set and test the model on test data set.

5.Accuracy check: - checked that how much accurate our value are.


What I have done:-

1.Import various libraries 
=• Pandas • Numpy • Seaborn • Matplotlib • Sklearn

2.Load the dataset
=Read the csv file using pandas.

3.Understanding the data
=Due to some confidentiality issues, the original features are replaced with V1, V2, … V28 columns which are the result of PCA transformation applied to the original ones. The only features which have not been transformed with PCA are ‘Time’ and ‘Amount’. Feature ‘Class’ is the response variable and it takes value 1 in case of fraud and 0 otherwise.
4.After,this we visualize  all the features(i.e. V1,V2---V28) from the dataset on graphs.

5.Then,separate the Fraudulent cases from the authentic ones and compare their occurrences in the dataset.Filter the columns to remove data we do not want

6.Using Skicit learn :
Split my data into two parts: - Train data and Test data.

7.define outlier detection tools to be compared,fit the data and tag outliers,Reshape the prediction values to 0 for valid, 1 for fraud and then Run classification metrics

8.Used  ML algorithm: - • Isolation Forest  - Accuracy got 0.9975 • Local Outlier Factor: - Accuracy got :0.9965
