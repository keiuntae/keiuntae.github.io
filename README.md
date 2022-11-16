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

![](/images/movies.jpeg)

# [Project 4: Movie Database: Project Overview]( https://github.com/keiuntae/keiuntae.github.io/tree/main/Movie%20Database)

* This project builds a movie database and generates a poster of the movie by reading an API.
1.	Import libraries 
2.	Load the secret API key from a JSON file and store in the same folder into a variable
3.	Assign the portal to a variable
4.	Write a utility function `print_json` to print nicely the movie data from a JSON file and define the print _json function 
5.	Define the saved_poster function
6.	Define the find_movie function
7.	Search for desired movie

![]( Movie%20Database/Weeks%209%20%26%2010%5CPosters%5C/Weeks%209%20%26%2010%5CPosters%5CThe%20Godfather.jpg)

# [Project 5: House Price Prediction: Project Overview](https://github.com/keiuntae/keiuntae.github.io/tree/main/House%20Price%20Prediction)

* This project uses linear regression to predict sale price based on dependable data. 
* Data was obtained from a housing dataset from Kaggle that examines data from various cities with several attributes:
  *	Date
  *	Price
  *	Number of bedrooms
  *	Number of bathrooms	
  *	Square foot of total living space
  *	Square foot of the lot
  *	Number of floors
  *	Waterfront status
  *	View rating
  *	Condition rating
  *	Square foot of above
  *	Square foot the basement
  *	Year built
  *	Year renovated
  *	Street Address
  *	City
  *	State/Zip Code
  *	Country

![](/images/distplot.png)

# [Project 6: ALS Predictive Analysis: Project Overview]( https://github.com/keiuntae/keiuntae.github.io/tree/main/ALS%20Predictive%20Analysis)

* This project uses principal component analysis to reduce dimensionality and clusters using ALS data.
1.	Load the data and necessary libraries
2.	Remove any data that is not relevant to the patient’s ALS condition.
3.	Apply a standard scaler to the data.
4.	Create a plot of the cluster silhouette score versus the number of clusters in a K-means cluster.
5.	Fit a K-means model to the data with the optimal number of clusters 
6.	Fit a PCA transformation with two features to the scaled data.
7.	Make a scatterplot of the PCA transformed data coloring each point by its cluster value.

![](/images/PCA%20Cluster%20Scatterplot.png)

# [Project 7: Retail Sales Time Series Modeling: Project Overview]( https://github.com/keiuntae/keiuntae.github.io/tree/main/Retail%20Sales)

* This project predicts monthly retail sales by building and fitting an AR model.  
1.	Import libraries and load data
2.	Plot the data with proper labeling and make some observations on the graph.
3.	Split this data into a training and test set.
4.	Use the training set to build a predictive model for monthly retail sales.
5.	Use the model to predict the monthly retail sales on the last year of data.
6.	Report the RMSE of the model predictions on the test set.

![](/images/retail%20sales.png)

