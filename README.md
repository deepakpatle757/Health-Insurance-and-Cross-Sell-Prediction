# HEALTH INSURANCE CROSS SELL PREDICTION

This is a note book of exploratory data analysis on cross selling of health insurance customers on vehicle insurance product and using machine learning to predict whether a customer is interested or not in vehicle insurancen

# Background Information :
* An Insurance company that provide Health Insurance to its customers, usually they offer other insurance product to the customers through diffirent kind of marketing channel. In this case we will build a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
# Problem Statement:
* Un optimize customer reachout process, many insurance worker spend a lot of their time having meeting with prospective client without knowing the probabily of that customer to buy the insurance product
# Business Goals:
* Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue
# Business Question:
* How does age of a vehicle determing the response of vehicle insurance advertisment
* How to attract customers from different generation
* what's the major factor that make a health insurance customer not intersted with vehicle insurance
* What's the best machine Learning modeling for this Cross Sell case
# Workflow :
* Data Cleaning
  * Recategorize Data
  * Binning
* Exploratory Data Analysis to Answer business Question

* Feature Engineering & Selection For Machine Learning Process

  * Encoding all the categorical features
  * Checking correlation between dependent and independet variable
  * Feature Selection
* Model Building :

  * Splitting data into Training and Testing
  * Creating base model of classification algorithm ( Logistic Regression, KNN Classifier, Decision Tree Classifier, Random Forest Clasifier)
  * Check The Evaluation matrix for all the base model
  * HyperParameter tuning
  * Checking Evaluation Matrix for tuned Model
  * Choose which model has the best recall score for this case
# Conclusion:
* From this dataset of health insurance customers almost 95% of customers have a vehicle age that's less than 2 years. from our analysis, customers who has more than 2 years of vehicle age are more interested with vehicle insurance advertisment, while customers who has less then one year of vehicle age, only 4% of them are actually interesred with vehicle insurance
* We found out that customer who already have vehicle insurance are almost have no interest in another vehicle insurance. Our analysis shows that 99.9% of customers that have a vehicle insurance is not interested in another vehicle insurance, while customer who doesn't have a vehicle insurance 22.5 % of them are interested with vehicle insurance
* We also found out that a newer vehicle are more likely to have a vehicle insurance, with vehicle that's less than one year 66% of those are insured , vehicle that's older than one year but less than 2 years are 33% insured, while less than one percent of vehicle that's older than 2 years are insured. This should explain why customer who owns a newer vehicle are less likely to be intersted with insurance promotion, because they probably alredy have one.
* Customers who never had vehicle damaged only 0.5 % of those customers are intersted with vehicle insurance, 87% of customers who never had any vehicle damaged already have a vehicle insurance
* Which Customer Generation are less likely to be intersted with vehicle insurance the answer is Millenials (people in age group of 18 - 34) only 6% of millenials are actually interested with vehicle insurance, and why is so?
  1. Almost 63% of millenials already have vehicle insurance, from our analysis before owning vehicle insurance is a major factor why someone is not interested with another vehicle insurance
  2. 90% of millenials have a vehicle that's less than one year of age, and from our analysis before that vehicle that's less than one year are 66% already insured

This conculed that millenials are more likely to already have a vehicle insurance before our vehicle insurance team approached, and that's a major factor why millenials are least likely to be interested with our vehicle insurance, because they already have one
