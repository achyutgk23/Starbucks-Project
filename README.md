# Table of Contents
1. Project Motivation
2. Installations
3. File Descriptions
4. Results Discussion
5. Licensing, Author, and Acknowledgement

## 1. Project Motivation
- The Starbucks project attempts to capture the perception of the customers toward promotional offers.
- This project tries to explore the purchasing behavior of customers when presented with promotional offers.
- The main goal of this project is to identify the group of customers who respond positively to promotional offers and those who do not respond to promotional offers.
- The motivation for this project is "to identify the groups of people who are most responsive to different offer types and how best to present each offer type to these groups of people."

## 2. Installations
- This project uses no other external libraries which doesn't come with basic installation of Anaconda distribution of python. The python 3 which comes with basic installation of Anaconda distribution will be sufficient to run the codes.

## 3. File Descriptions
- A jupyter notebook which contains python code used which is used for predictive analysis
- A data folder which contains 3 json files viz. profile.json, portfolio.json, and transcript.json.These three datasets will constitute the input space.
- A README.md file which provides the basic introduction to the project and guides the users throughout the project.

## 4. Results Discussion
- Random forest classifier was used to make predictions on the test set.
- Among different classifiers, random forest classifier was the best individual classifier with cross-validation F1 score of 0.8387.
- When the hyper-parameters of the random forest model were tuned using grid search cv function, the F1 score increased about only 1%.
- Then, with appropriate decision threshold value, which provides desirable precision and recall scores, the predictions were made on the test set.
- The precision, recall and F1 score of the model on the test set are 0.723, 0.952, and 0.822 respectively.
- The full discussion on the results of the analysis can be found [here](https://achyutk23.medium.com/starbucks-promotional-offers-project-339db34a95d0)

## 5. Licensing, Author, and Acknowledgement
- The views expressed int project are my own and the credit for the dataset goes to Starbucks and credit to udacity for making the dataset available.
