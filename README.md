
# Credit Card Fraud Detection.

Here, result is only in Credit Card Fraud yes or no format So
We are going to  use Logistic Regression Machine learning model.


## Work Flow:


importing Credit card data 

Data Preprocessing 

Data Analysis

Train Test split

Train model using Logistic Regression model

Evaluation of model



## Importing Dependencies:

import numpy as np

import pandas as pd

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression

from sklearn.metrics import accuracy_score




## Data Set Link:

   data set are downloaded from the kaggle website.
   
   
## Funtion and Methods Used in Skeleton format:

        Function and Methods help to analyse the data .
        and help to follow the forward path .

pd.read_csv()

.head()

.tail()

.info()

.isnull()

.value_count()

       it gives the value and count of that value into the column
       Used to check the balance of data value.

.describe()

.groupby()

.sample(n= )

       here data is in form of unbalacned format so make in balnce format we 
       selecting the same amount of data using .sample() function.

.concat()

LogisticRegression()
       Here,  result is in the binary format so 
       we using this model.



