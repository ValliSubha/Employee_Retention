# Employee_Retention

## Employee Retention using Machine Learning Techniques
Done by R.Valli Subha

Under the guidance of Dr. David Raj Micheal

### Objective of the project :
In this proposed research work, we have implemented the Machine Learning (ML) and Natural Language Preocessing (NLP) techniques in handling the feedback reviews and ratings collected from 6 different MNCs and the comparison of their performances based on their employee’s reviews and opinions. The project aims to develop an optimized model and sentimental analysis for predicting employee retention. We'll also look at the factors that cause employee attrition and find which company makes best effort in retaining their employees with the use of the given feedback reviews and ratings data.

### Methodology:
we have employed the techniques of Natural Language Processing for text preprocessing where we have implemented text cleaning, tokenization and corpora. We have removed the noise and missing values and have replaced the mean values in their respective spaces. Then, we did exploratory data analysis to address few problem statements and utilized sentiment analysis using VADER package to find the polarities and sentiment scores from the text reviews. Later in findings and analysis part, we applied various ML algorithms - the model classifiers that would illustrate the features that affect the employee's decision and predict the probability of the similarities between the provided feedback reviews and ratings. We also implemented MANOVA to find the significant difference between the reviews given by the current and former employees. Finally we studied the factors affecting employee retention using the results and analysis.

Dataset : https://www.kaggle.com/saqlainrehan/employeesreviews-dataset
The dataset consists of 67529 records and 16 variables among which seven are numeric variables which include numeric and star ratings given by the employees from 1 to 5, and four are text variables including summary, pros, cons, and advice to management by the reviewer employee.

Columns :
Company, Location, Dates, Job title, Summary, Pros, Cons, Adivce to management, Overall ratings, Work-balance stars, culture-values stars, compensation-benefits stars, senior-management stars, helpful-count and link (glassdoor review link)
