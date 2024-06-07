
                      Syriatel Customer Churn Prediction Project 

                                   Overview


This binary classification project focuses on conducting a churn analysis for SyriaTel, a telecommunications company based in Syria. The objective is to uncover the factors influencing customer churn and to build a classifier capable of predicting which customers are prone to churn. By identifying these customers in advance, SyriaTel can take proactive measures to mitigate customer attrition and retain their client base effectively.


                              Goal of the project

The goal is to create a machine learning model capable of predicting the likelihood of a customer discontinuing a service, as well as identifying the factors contributing to this churn.

                                Objectives
- To find out why customers are leaving.
- To see which factors affect customer leaving the most.
- To make a model that can predict if a customer might leave.
- To check how well the model works and compare it with others.
- To find ways to stop customers from leaving and keep more of them.
- To make a plan to use the ideas from the model to stop customers from leaving.
- To watch and see how well the plan works over time in stopping customers from leaving and how it affects the business.

                             Business Understanding.

Syriatel faces a challenge: a significant number of customers are departing for rival companies. To tackle this, they aim to develop a tool capable of forecasting customer churn. By analyzing their data to discern the reasons behind customer departures, they plan to construct a predictive model to anticipate when a customer might defect. This initiative is designed to empower Syriatel to proactively address customer concerns, enhance satisfaction, and prevent churn.
                             
                               Data Exploration
     
This project uses the SyriaTel Customer churn data set which is retrieved from Kaggle: https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset. The data used has been sourced from Kaggle. The dataset contains a record of 3333 rows and 21 columns (4 are categorical and 17 are numerical ) containing different features.

                           Data Cleaning and Data analysis

I examined the dataset to identify any instances of missing or null values and duplicates but there were not missing values and duplicates.
I did Univariate , Bivariate and Multaviriate analysis to provide a comprehensive understanding of the dataset, uncover underlying patterns and relationships, and inform further modeling and decision-making processes.

                             Uvivariate Analysis   

    ![Target variable](![alt text](image-4.png))


From the graph depicted above, it can be observed that approximately 483 customers out of the total 3333 in the dataset have terminated their contracts with the telecommunication company.
I also came up with histogram illustrating the distribution of all numerical features, revealing that the majority of features exhibit a curve resembling a normal distribution.