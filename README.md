## Project Description

In this project, I will be working with a pharmaceutical research dataset to compare the performance of the drug "Capomulin" versus other treatment regimens for squamous cell carcinoma (SCC), a commonly occuring form of skin cancer. The focus of my project will be to create visualizations using Matplotlib to prove or disprove Capomulin's effectiveness. 

## Features & Libraries

* Python 
* Matplotlib
* Pandas
* Scipy
* Numpy

## My Process

1. check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.
2. Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
3. Generate a bar plot that shows the number of total mice for each treatment regimen throughout the course of the study.
4. Generate a pie plot that shows the distribution of female or male mice in the study.
5. Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
6. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
7. Generate a box and whisker plot of the final tumor volume for all four treatment regimens.
8. Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
9. Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
10. Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.