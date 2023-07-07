# Intern Hiring Project

## Project Description

This project aims to develop an algorithm to identify the best candidate for an internship position based on their skills and attributes. The dataset used in this project contains information about various candidates, including their proficiency in Python, Machine Learning, Natural Language Processing (NLP), Deep Learning, and other skills. The dataset also includes information about the candidate's availability for the internship, their degree, stream, and the current year of graduation.

The project involves several steps:

1. **Data Loading**: The data is loaded from a CSV file hosted on Google Drive.
2. **Data Cleaning**: The data is cleaned by handling missing values and removing duplicates. The 'Other skills' column, which is a string of skills separated by commas, is converted into a list of skills.
3. **Feature Engineering**: A scoring system is defined to calculate a total score for each candidate based on their skills and attributes. The scoring system considers the scores for Python, Machine Learning, NLP, and Deep Learning, as well as the number of other skills, the degree, and the year of graduation.
4. **Model Training and Evaluation**: A machine learning model is trained to predict the total score of a candidate based on their skills and attributes. The model is evaluated using the root mean squared error (RMSE) metric.
5. **Best Candidate Selection**: The candidate with the highest total score is identified as the best candidate for the internship.

The project is implemented in Python using libraries such as pandas for data manipulation, scikit-learn for machine learning, and Faker for generating fake data.

## Files in the Project

- `Intern_Hiring_Algorithm.ipynb`: This is the main Jupyter notebook file containing all the code for the project.

## How to Run the Project

1. Clone the GitHub repository to your local machine.
2. Open the `Intern_Hiring_Algorithm.ipynb` file in Jupyter Notebook.
3. Run all the cells in the notebook.
