
# IMDB Movie Dataset Analysis and Rating Prediction

## Project Overview
This project explores the (IMDB movie dataset (2023)) through data cleaning, visualization, and a simple machine learning model.  
The goal is to understand patterns in movie ratings, genres, and votes, and to build a regression model to predict ratings.

## Dataset
- **Source:** Kaggle IMDB Movie Dataset (Dec 2023)  
- **Size:** Contains information about movies, including:
  - Title
  - Genre
  - Year
  - Rating
  - Votes
  - Meta Score

## Tools & Libraries
- Python 3
- Pandas & NumPy (data manipulation)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (linear regression, model evaluation)

## Exploratory Data Analysis (EDA)
- Checked for missing values and cleaned the dataset
- Converted release year into proper numeric format
- Visualized:
  - Distribution of movie ratings
  - Number of movies per genre
  - Relationships between ratings, votes, and meta scores

## Key Visualizations
- Histogram of movie ratings with KDE
- Bar chart of movie genres
- Scatter plot of actual vs predicted ratings
- Correlation heatmap (optional extension)

## Machine Learning Model
- **Model:** Linear Regression
- **Features (X):** Votes, Meta Score  
- **Target (y):** Rating  
- **Evaluation Metric:** Mean Squared Error (MSE)  

The model predicts IMDB ratings based on votes and critic scores.

## Results
- Average movie rating across the dataset
- Genre frequency distribution
- Regression model performance (MSE and visualization of actual vs predicted ratings)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/imdb-movie-analysis.git
Install required libraries:

bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook or .py script and run all cells.
