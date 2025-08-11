# Swiggy-python-
This repository contains a data analysis project focused on Swiggy restaurant data. Using Python and key data science libraries like Pandas, NumPy, Matplotlib, and Seaborn, the project explores market trends, customer preferences, and restaurant performance
Swiggy Data Analysis with Python
Project Objective
The goal of this project is to perform an in-depth data analysis on a dataset of Swiggy restaurant data. By leveraging Python libraries like Pandas, Matplotlib, and Seaborn, the analysis aims to uncover valuable insights into restaurant performance, customer preferences, and key market trends.
The findings from this analysis can be used to inform business decisions related to marketing strategies, menu optimization, and identifying new business opportunities.
Technologies and Libraries Used
•	Python: The core programming language for the analysis.
•	Jupyter Notebook: The development environment for interactive coding and visualization.
•	Pandas: A powerful library for data manipulation and analysis.
•	NumPy: A fundamental library for numerical operations.
•	Matplotlib: A versatile plotting library for creating static, animated, and interactive visualizations.
•	Seaborn: A statistical data visualization library built on top of Matplotlib, offering a high-level interface for drawing attractive and informative plots.
Project Structure and Methodology
The analysis is structured into several key stages, each addressed in the Jupyter Notebook:
1. Data Loading and Initial Exploration
•	The raw swiggy_scrap_uncleaned.csv dataset is loaded into a Pandas DataFrame.
•	Initial checks are performed to understand the data's structure, including its shape (df.shape), the first few rows (df.head()), and data types (df.info()).
2. Data Cleaning and Preprocessing
This is a critical step to ensure data quality and accuracy. Key cleaning tasks include:
•	Feature Engineering: The rating_and_delivery_time column, which contains combined data, is split into two new columns: rating and delivery_time.
•	Data Type Conversion: The newly created rating and delivery_time columns are converted to appropriate numerical types (float and int) for mathematical operations.
•	Handling Missing Values: Any missing values (e.g., in the rating column) are addressed by either removing or filling them appropriately.
•	Text Cleaning: The offer and food_type columns are cleaned to extract relevant information, such as whether an offer exists, the maximum discount amount, and individual food cuisines.
3. Exploratory Data Analysis (EDA)
This stage involves using visualizations to understand the data better and identify trends. The notebook generates several plots, including:
•	A bar plot to visualize the distribution of restaurants across different rating categories (e.g., 'Excellent', 'Good').
•	An analysis of the distribution of delivery times.
•	Visualizations to identify the top N most common food cuisines.
4. Key Findings
•	The analysis provides insights into the average ratings and delivery times of restaurants.
•	It highlights the most popular food cuisines in the dataset.
•	It helps identify the different categories of offers and their prevalence among restaurants.
Feel free to open the Swiggy(python).ipynb notebook to see the code and visualizations in detail. Any contributions or suggestions for further analysis are welcome!

