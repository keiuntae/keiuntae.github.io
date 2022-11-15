### Hi there 👋

I'm Keiuntae Smith and I am a current student attending Bellevue University working on My Masters for Data Science. 

### Contact Information
tramal23@hotmail.com

# Data Science Portfolio
This is my portfolio containing a repository of data science projects completed by me for academic, self learning, and hobby purposes. Presented in the form of Jupyter notebooks, and R markdown files (published at RPubs).

## Instructions for Running Python Notebooks Locally
1. Install dependencies using requirements.txt.
2. Run notebooks as usual by using a jupyter notebook server, Vscode etc.

# [Project 1: Breast Cancer Prediction: Project Overview](https://github.com/keiuntae/keiuntae.github.io/tree/main/Breast%20Cancer%20Prediction)
* Created a tool that predicts breast cancer through machine learning tactics by use of breast cancer data.
* Utilized a Wisconsin breast cancer diagnostic data set from the UCI Machine Learning Repository
* Optimized Logistic, Nearest Neighbor, Support Vector, Decision Tree, and Random Forest regressors to reach best model.

![](/images/Model%20Accuracies%20Plot.png)

# [Project 2: MLB Attendance: Project Overview](https://github.com/keiuntae/keiuntae.github.io/tree/main/MLB%20Attendance)
* Use MLB data to make a recommendation on how to improve attendance
* Data was obtained from the Los Angelas Dodgers Major League Baseball team

![](/images/MLB%20Correlation%20Heatmap.jpeg)

# [Project 3: Movie Recommender: Project Overview](https://github.com/keiuntae/keiuntae.github.io/tree/main/Movie%20Recommender)
* Using several datasets to build a recommender system for movies by correlation tactics and utilization of pivot tables
1.	Load libraries
2.	Load the ratings dataset and preview the first 10 rows
3.	Load the movie titles dataset and preview the first 10 rows
4.	Merge the two dataframes into one
5.	Preview the first 10 rows of the new dataframe
6.	Create a new dataframe that displays average rating (mean) for each movie in the data
7.	Dreate a dataframe that shows the total ratings cast for each movie
8.	Calculating the Correlation by making a pivot table (rows=userID, columsns=Movie Title)
9.	Preview the first ten rows pivot dataframe
10.	Create a correlation value using the 'corrwith' function in conjunction with a movie choice
11.	Display the first five rows of computed pairwise correlation between rows and columns
12.	Create a new variable named 'recommend' and drop all the empty values
13.	Merge the ratings to the correlation table
14.	Filter all movies that are correlated to 'Godfather, The (1972)' using the sort_values function
15.	Merge the original movie dataset to show all fields
16.	Display the recommended list dataframe to include the movie selection and ten recommended movies (Nair, 2019)
