# Movie Profit Analysis Using Python
📌 **Project Overview**
This project analyzes movie metadata to understand the relationship between production budget, revenue, and profit in the film industry. The analysis uses movie metadata and rating datasets to explore how films perform financially and how audiences rate them.
The workflow includes data import, data cleaning, feature engineering, and exploratory data analysis (EDA) using Python. A new feature called **profit** is created by subtracting budget from revenue to evaluate movie profitability. Visualization techniques such as histograms and boxplots are used to understand the distribution of profit and movie ratings.
The results provide insights into profit distribution in the film industry and reveal how audiences generally rate movies.


🎯 **Objectives**
* Analyze the distribution of movie **budget, revenue, and profit**
* Identify patterns in movie financial performance
* Perform **Exploratory Data Analysis (EDA)** to understand dataset characteristics
* Analyze user ratings to evaluate movie quality from audience perspectives
* Generate insights that help understand movie performance trends

📊 **Key Metrics Analyzed**
* Movie production **budget**
* Movie **revenue**
* Movie **profit (revenue – budget)**
* **Profit distribution** across movies
* **Outlier detection** in profit values
* **User rating distribution**
* Median movie ratings per film

🔍 **Key Insights**
* Only a small number of movies generate extremely high profits, creating **profit outliers** in the dataset.
* Most movies have profit values near the lower range compared to blockbuster films.
* The distribution of movie ratings is concentrated between **3 and 4**, indicating that most movies are rated fairly positively by viewers.
* Very low ratings (below 2) are relatively rare.
* Movies with very high ratings (close to 5) exist but represent a small portion of the dataset.

🛠 **Tools Used**
* **Python**
* **Pandas & NumPy** – data manipulation and analysis
* **Matplotlib & Seaborn** – data visualization
* **Google Colab** – analysis environment
* **Dataset:** Movie Metadata & Ratings Small (Kaggle)

📂 **Project Workflow**
1️⃣ **Data Import & Understanding**
Import movie metadata and ratings datasets and explore dataset structure, columns, and data types.
2️⃣ **Data Cleaning & Preparation**
Convert data types (such as release dates), check unique values, and prepare the dataset for analysis.
3️⃣ **Feature Engineering**
Create a new feature called **profit** by calculating the difference between revenue and production budget.
4️⃣ **Exploratory Data Analysis (EDA)**
Visualize profit distribution using histograms and detect outliers using boxplots.
5️⃣ **Rating Analysis**
Analyze user rating distributions and calculate median ratings for each movie.

📈 **Business Recommendations**
* Conduct further analysis on movies with **very low ratings (<2)** to identify possible factors such as genre, production quality, or cast performance.
* Use rating distributions to support **movie recommendation systems** that highlight films with higher audience satisfaction.
* Prioritize movies with **ratings above 4** as recommended content since they represent higher audience approval.

📝 **Notes**
* The dataset used in this project comes from **Kaggle and is used for educational purposes**.
* This project focuses on **Exploratory Data Analysis (EDA)** rather than predictive modeling.
* Future improvements may include:
  * Genre-based profitability analysis
  * Correlation analysis between budget, revenue, and ratings
  * Building a **movie recommendation system**
  * Applying machine learning models for **revenue prediction**
