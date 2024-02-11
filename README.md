# Market-Analysis-of-Health-and-Fitness-AI-app
This repository analyzes activity tracking data using Python and explores key features such as distance, calories, and heart rate. A linear regression model is implemented to predict the number of steps based on various parameters. 

# Activity Tracking Data Analysis and Linear Regression Model

## Overview
This repository contains code for analyzing activity tracking data and building a linear regression model to predict steps based on various features. The dataset used is 'Activity_tracking_data.csv'.

## Exploratory Data Analysis (EDA)
- Loaded the dataset and displayed its shape.
- Displayed the first 10 rows of the dataset to get an initial understanding.
- Plotted a histogram of 'Total Calories' to visualize its distribution.
- Created a pair plot and correlation heatmap to explore relationships between features.

## Calorie Bins Analysis
- Created 'Calorie_Bins' based on specified bins and visualized average distance, average average heart rate, average total calories, and average elapsed time by calorie bin.

## Linear Regression Model
- Selected features ('Distance', 'Calories', 'Avg HR', 'Total Reps', 'Total Sets', 'Elapsed Time (hours)', 'Total Calories') and the target variable ('Steps').
- Split the data into training and testing sets.
- Initialized a linear regression model.
- Trained the model on the training set.
- Made predictions on the testing set.
- Evaluated the model using Mean Squared Error (MSE).
- Visualized actual vs predicted values using a scatter plot.

## How to Use
1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Install the required dependencies: `pip install -r requirements.txt` (if there is one)
3. Run the Jupyter Notebook or Python script for your analysis.


