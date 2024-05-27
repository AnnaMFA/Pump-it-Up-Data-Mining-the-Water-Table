# Pump-it-Up-Data-Mining-the-Water-Table
Project for the Machine Learning module of the Master's in Data Science, Big Data, and Business Intelligence at Complutense University.

## About this project.
This project is my contribution to the online and open competition 'Pump it Up: Data Mining the Water Table' on DrivenData consist in predict the state or condition of several waterpoints across Tanzania. The labels of the waterpoint status are: functional, functinal needs repair and non functional. There are 3 datasets: training dataset, test dataset and labels. 

## Step by Step of my project
First of all, I began by analyzing and transforming the 40 columns of the training and test datasets. I started with the training data, dividing them into numerical variables and categorical variables. I eliminated the 'num_private' variable as it was not significant and created graphical representations of the numerical variables to visualize their distribution and determine which ones might be significant for the model.

Regarding the categorical variables, I binarized the 'public_meeting' and 'permit' variables, which have True and False values, to analyze them as numerical variables. I transformed the 'date_recorded' variable to create a column for each part of the date (one column for the day, another for the month, and another for the year). For the remaining categorical variables, in preparation for applying a Random Forest model, I applied LabelEncoder transformation. For the application of other models, I used OneHotEncoder for variables with fewer than 10 different data types.

I performed some additional transformations to apply various Machine Learning classification models, such as Logistic Regression, Decision Trees, and again Random Forest, eliminating some variables that were considered in the first applied model.

I applied a total of 7 models, achieving the highest score of 0.81 with the first Random Forest model applied.

![Captura de pantalla (53)](https://github.com/AnnaMFA/Pump-it-Up-Data-Mining-the-Water-Table/assets/168220709/5f1d52ff-21ad-4c33-8807-aabf83bc63da)
