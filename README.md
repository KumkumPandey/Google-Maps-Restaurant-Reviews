Google Maps Restaurant Review Analysis & Prediction
Introduction:
This project focuses on analyzing restaurant review data scraped from Google Maps. I've used a complete data science workflow to clean and process the data, build machine learning models to predict review sentiment and ratings, and then visualize the key insights in an interactive Power BI dashboard. This project demonstrates skills in data manipulation, predictive modeling, and data storytelling.

Key Highlights:
Data Analysis (Jupyter Notebook): I performed data exploration and cleaning on raw review data. I also engineered a new feature, review_length, from the review text to be used in the predictive models.

Machine Learning Models: I built two types of models to gain deeper insights into the data:

Sentiment Classification: A Logistic Regression model was trained to classify review text as either positive or negative.

Rating Prediction: I used Random Forest and Decision Tree regressors to predict a restaurant's star rating based on features like sentiment and review length.

SQL Integration: I demonstrated proficiency in SQL by simulating a database environment within the Jupyter Notebook. I performed key operations like JOIN and GROUP BY to prepare the data for analysis.

Interactive Dashboard (Power BI): The final output is a multi-page Power BI dashboard that presents the project's findings. It includes a main summary page, a detailed review page, and a sentiment analysis page, making the insights easily accessible and interactive.

Tools & Technologies:
Programming Language: Python

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Power BI, MS Excel

Machine Learning: Scikit-learn

Database: SQLite (in-memory)

Environment: Jupyter Notebook, Power BI Desktop

Outcomes & Analysis:
The project provided several key findings from the data analysis and predictive modeling:

Sentiment Analysis: The Logistic Regression model achieved an overall accuracy of over 81% in predicting sentiment from review text. However, a key finding from the classification report was that the model struggled to accurately identify negative reviews.

Rating Prediction: The regression models were able to predict ratings with a Mean Absolute Error (MAE) of around 1.07. This suggests that while sentiment and review length have some predictive power, other features would be needed to improve the model's accuracy.

Dashboard Insights: The Power BI dashboard effectively visualizes the distribution of ratings, the breakdown of sentiments across different review categories, and provides a way to drill down into the raw text of individual reviews. These visualizations help a user quickly understand a restaurant's overall performance.
