# Bank-Marketing-Effectiveness-Prediction
 
# **Problem statement :-**

- The banking institution conducted a marketing campaign based on phone calls. The records of their efforts are available in the form of a dataset. The objective here is to apply machine learning techniques to analyse the dataset and figure out most effective tactics that will help the bank in next campaign to persuade more customers to subscribe to banks term deposit.
- Bank profitability depends on long-term deposits. Targeted marketing tactics that let customers interact with banks directly are the main focus of bank marketing.


# **Project Summary :-**

- Banks are required to sell more long-term bank deposits to enhance their cash reserves right ? 
- Bank profitability depends on long-term deposits and Marketing executives are therefore under pressure to persuade the general public to buy long-term deposits. To increase the positive response rate, marketing managers should build better use of their limited resources by making fewer calls to customers while closing more sales. Because they already contain data from prior campaigns to examine, managers may utilize data classification techniques to determine clients in near future.
- The dataset class is labelled as ‘yes’ or ‘no’ depending on whether the contacted client has subscribed to the term deposit or not. It is a marketing problem and the outcome will largely influence the future strategies of bank. Banking institute has a very large client base and even larger target clients. 
- In real world , less clients will respond positively to marketing campaign and most of them will say no. Contacting all of them is time consuming task and demands tremendous time and efforts. To manage the human resource in efficient way, it is necessary to correctly identify those clients who have more chances of saying yes. This is where machine learning comes into picture.


## **Objective :-**

- The main objective is to build a predictive model that predicts whether a new client will subscribe to a term deposit or not, based on data from previous marketing campaigns.


## **Dataset Info :-**

* Number of records: 45,211
* Number of features: 17

  ## **The dataset contains features like :-**

**Bank Client data :**

`Age :-` This is age of client.

`Job :-` The job of clients. It has 12 categories including unknown.

`Marital :-` Marital status of the customer. It has 3 categories.

`Education :-` The level of education of the customer.

`Default :-` It tells whether the customer has credit in default or not.

`Balance :-`  It specifies the account balance of the customer.

`Housing :-` Whether the customer has a housing loan or not.

`Loan :-` Whether the customer has a personal loan or not.

---
**Related with the last contact of the current campaign :**

`Contact :-` The method of communication used to contact the customer.

`Month :-` The month of the year on which the customer was last contacted.

`Day :-` The day of the month on which the customer was last contacted.

`Duration :-` The duration of the last contact with the customer in seconds.

---
**Other attributes :**

`Campaign :-` The number of contacts performed during the current marketing campaign for this customer.

`Pdays :-` Number of days passed by after the customer was last contacted from a previous campaign. some value is **-1** if the client was not contacted previously.

`Previous :-` Number of times this client was contacted before this campaign.

`Poutcome :-`The outcome of the previous marketing campaign for this customer.

`Deposit(y) :-` Whether the customer has subscribed to a term deposit Yes or No. (the target variable)

# **Project Work flow :-**

- **Importing Neccessary Libraries**
- **Data Wrangling**

```
      ▪ Gathering Data 
      ▪ Assessing Data
      ▪ Cleaning Data 
```

- **EDA**

```
      ▪ Univariate Analysis
      ▪ Bivariate Analysis
      ▪ Multivariate Analysis
 
```
- **Features Engineering**

```
      ▪ check Outliers
      ▪ features transformation
      ▪ features construction
      ▪ features selection
```

- **Remove Multicollinearity**
- **pre-processing**

```   
      ▪ preprocessing columns
      ▪ Splitting Dependent and Independent Variables
      ▪ Handling imbalance class
```

- **Model implementation and HyperParameter Tuning**

```
      ▪ Train, Test and Split
```

- **Final selection of the model**
- **Conclusion**

- # **Algorithms used for ML model implementation :-**

* **`Logistic Regression (LR)`**
* **`Decision Tree`**
* **`RandomForest Classifier`**
* **`K-nearest Neighbour Classifier (KNN)`**
* **`Naive Bayes`**
* **`SVM Classifier`**
* **`Light Gradient Boost`**
