
## Project Members

Samuel Dribsa>> https://github.com/Samidirbsa
Keith Omollo>> https://github.com/K-OMOLLO
Emill Maglo>> https://github.com/SiperMaglo
Monica Nyambura>> https://github.com/M-travis123
Angelia Nakkungu>> https://github.com/Nakkungu
Pascal Wambua>>

 ## Description

Welcome to a compelling journey into the realm of time series forecasting! In this project, we embark on the intriguing challenge of predicting store sales using data from Corporation Favorita, a prominent grocery retailer based in Ecuador. As we delve into the intricacies of this task, our primary objective is to construct a robust model capable of accurately predicting the unit sales for a myriad of items across various Favorita stores.

The foundation of our predictive prowess lies in a diverse array of data points, including dates, store and product details, information about promotional activities, and, crucially, the corresponding sales figures. Our dataset is enriched with supplementary files containing additional information, providing a wealth of insights that can be harnessed to enhance the predictive capabilities of our models.

Join us as we navigate through the nuances of this time series forecasting problem, unraveling patterns, and leveraging comprehensive data to build a model that not only forecasts sales accurately but also unveils the underlying dynamics of retail operations within Corporation Favorita. Your journey begins here, where data science meets the world of retail, promising a captivating exploration of analytics and forecasting.

## **Data Field Information:** ##

**1. train.csv:**
Description: The training data, comprising a time series of features including store_nbr, family, onpromotion, and the target variable sales.
Data Fields:
store_nbr: Identifies the store where products are sold.
family: Identifies the type of product sold.
sales: Total sales for a product family at a specific store on a given date.
onpromotion: Total number of items in a product family that were being promoted at a store on a given date.

**2. test.csv:**
Description: The test data, having the same features as the training data. Used to predict target sales for the 15 days after the last date in the training data.
Data Fields:
Same as the train.csv data fields.

**3. transaction.csv:**
Description: Contains information about transactions made on specific dates.
Data Fields:
date: Date of the transaction.
store_nbr: Identifies the store where the transaction occurred.
Additional details about the transaction.

**4. sample_submission.csv:**
Description: A sample submission file in the correct format.

**5. stores.csv:**
Description: Store metadata, including city, state, type, and cluster. Cluster represents a grouping of similar stores.
Data Fields:
store_nbr: Identifies the store.
city: City where the store is located.
state: State where the store is located.
type: Type of the store.
cluster: Grouping of similar stores.

**6. oil.csv:**
Description: Daily oil prices, including values during both the train and test data timeframes. Given Ecuador's dependency on oil, its economical health is highly vulnerable to shocks in oil prices.

**7. holidays_events.csv:**
Description: Holidays and Events metadata, including information about transferred holidays.
Data Fields:
date: Date of the holiday or event.
Additional metadata about the holiday or event.

## **The Hypothesis**

### **Null Hypothesis (H0):** There is no significant difference in sales between promoted and non-promoted items.

### **Alternative Hypothesis (H1):** Items that are promoted have significantly higher sales compared to non-promoted items.

## **The Analytical Questions**

1. Is the train dataset complete (has all the required dates)?
2. Which dates have the lowest and highest sales for each year?
3. Did the earthquake impact sales?
4. Are certain groups of stores selling more products? (Cluster, city, state, type)?
5. Are sales affected by promotions, oil prices and holidays?
6. What analysis can we get from the date and its extractable features?

## **Prerequisites**

Before diving into the project, make sure you have:

Knowledge of Python Familiarity with utility libraries like Pandas, Numpy Basic understanding of visualization libraries like Seaborn, Matplotlib Implementable knowledge of SciKit Learn Understanding of concepts such as Data Transformation, Feature Engineering, Model Training, Model Evaluation, and Model Testing

## ** ## **Building Process**

Load the necessary datasets and libraries required for the project. Analysis:

Understand the structure of theS data, including columns, values, and data types. Visualization:

Use Seaborn and Matplotlib to visualize the dataset and grasp underlying patterns. Data Cleaning:

Dealing with missing values and clean the dataset. Feature Engineering:

Understand features and create new ones based on essential insights. Model Training:

Utilize algorithms like logistic regression, random forest to train the model. Evaluation:

Assess the predictive model's performance.

## * Testing:*

Test the model and compute accuracy through evaluation

Link to Dashboard 

https://app.powerbi.com/groups/me/insights/357fa118-b401-4f0b-ab0a-71e3191c33cd?insightsSource=Desktop&experience=power-bi





