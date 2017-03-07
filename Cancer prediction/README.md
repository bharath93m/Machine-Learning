#Cancer prediction using Logistic Regression and Naive Bayes

Packages Used: Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn

Steps Involved:
•	Data Acquisition
•	Exploratory Data Analysis
•	Data Cleaning – Training Data
•	Splitting Training Data into Train and Test
•	Model Training – Logistic Regression
•	Exploring results of other Models
•	Model Training – Naïve Bayes
•	Data Cleaning – Scoring Data
•	Scoring Data Model Training – Logistic Regression
•	Predicting value for the Survival variable using the model

Process description:
Started by importing the csv file using pandas into a data frame. Then performed exploratory analysis using seaborn to find any patterns in the data. Missing data has been imputed by mean, median, mode, regression and interpolation. Then training data has been split into 70-30 as train and test data. Data is initially trained using logistic regression which gave an accuracy of 68%. Other models have been explored to find for a more efficient algorithm of which Naïve Bayes reached an accuracy of 74%. But when examined, naïve Bayes resulted in more number of False Positives in the confusion matrix. Hence, proceeded to use Logistic regression as the model for prediction. Scoring data has been cleaned and transformed in a similar way to be fed into the model for prediction.

