# Telecom Churn Prediction and Analysis
> In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.


## Table of Contentss
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Model Building and Prediction](#model-building-and-prediction)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Understanding Customer Behaviour During Churn 
>> Customers usually do not decide to switch to another competitor instantly, but rather over a period of time (this is especially applicable to high-value customers). In churn prediction, we assume that there are three phases of customer life cycle :<br>

The ‘good’ phase: In this phase, the customer is happy with the service, usage and behaviour is normal.<br>

The ‘action’ phase: The customer experience starts to sore in this phase, for e.g. he/she gets a compelling offer from a competitor, faces unjust charges, becomes unhappy with service quality etc. In this phase, the customer usually shows different behaviour than the ‘good’ months. Also, it is crucial to identify high-churn-risk customers in this phase, since some corrective actions can be taken at this point (such as matching the competitor’s offer/improving the service quality etc.)<br>

The ‘churn’ phase: In this phase, the customer is said to have churned. You define churn based on this phase. Also, it is important to note that at the time of prediction (i.e. the action months).<br>

- Business Objectives :
>> For many incumbent operators, retaining high profitable customers is the number one business goal.
>> To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.



## Model Building and Prediction
- Data Cleaning and analysis
> - Null value check and outliers treatment is performed on the data.
> - As part of EDA, pariplot and correlation heat map among variables is compared. Box plots compared for the categorical variables and regression plots for numerical variables.
- Data preparations
> - Devired feature columns based on existing features and scenarios.
> - Filtering out high-valued customers.
> - Outliers elimination.
> - Data is splited into train and test sets, using sckitl learn libraries.

- Modelling the data
> - Build base model using PCA to reduce dimension of the data.
> - Build ML models like Logistic Regression, Decision Tree , Random Forest etc. on top of PCA model to fetch model prediction performance.
> - Build ML model ike Logistic Regression, Decision Tree , Random Forest, Boosting, Bagging etc. as a standalone model to understand feature importance.
> - Finalize most accurate model for final prediction.


## Conclusions
- Objective is to predict Churn, so instead of accuracy, Recall value will be considered as primary selection parameter.
- Top important features identified which helps business holder to understand Churn pattern of a Customer.
- Churn predicted on unseen data set using final model..


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - PYTHON
- library - PANDAS
- library - NUMPY
- library - MATPLOTLIB
- library - STATSMODEL
- library - SKLEARN


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@Soumayad96] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->