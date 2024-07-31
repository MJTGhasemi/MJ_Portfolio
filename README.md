# Portfolio

---

## Project Title: **Insights from Hotel Reviews: A Data-driven Approach to Customer Satisfaction**

### Project Overview

This project leverages data science to transform unstructured hotel reviews into structured, actionable insights, aiming to predict hotel ratings based on customer feedback. The analysis encompasses data wrangling, exploratory data analysis (EDA), and machine learning modeling to uncover and predict the layers of customer sentiment affecting the hospitality industry.

### [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/MJTGhasemi/Hotel_Reviews)

### Key Components

#### Data Wrangling
The dataset includes reviews from TripAdvisor, incorporating textual feedback and hotel metadata. The data cleaning process involved removing missing values and normalizing the text, setting the stage for detailed feature extraction and analysis.

#### Exploratory Data Analysis (EDA)
The EDA focused on word frequency and sentiment analysis to identify key themes from customer reviews. Techniques like word clouds and sentiment-specific visualizations were used to illustrate prevalent terms and emotions expressed by guests.

#### Machine Learning Modeling
Several machine learning algorithms, including logistic regression and random forest, were employed. The transformation of review text into TF-IDF vectors facilitated the training of predictive models, which were meticulously tuned to optimize performance.

### Final Report
The final report discusses the methodologies, results, and insights from the analysis, highlighting the predictive power of machine learning in interpreting customer reviews and guiding hotel management strategies.

### Key Findings
- Machine learning models can effectively predict hotel ratings from customer reviews.
- Sentiment analysis reveals critical factors influencing guest satisfaction.
- Textual feedback provides valuable insights for strategic improvements in service quality.

### Technologies Used
- Python
- Jupyter
- Libraries: Pandas, Numpy, Scikit-Learn, NLTK, SpaCy, Tensorflow

### Implications
The project demonstrates the importance of data-driven insights in the hospitality industry, offering a blueprint for enhancing customer satisfaction through strategic analysis and predictive modeling.

---

## Project Title: **Single-cell RNA Sequencing Analysis**

### Project Overview

This project explores the detailed dynamics of cellular differentiation and maturation using single-cell RNA sequencing (scRNA-seq) techniques. It covers extensive data wrangling, exploratory data analysis, and predictive modeling to investigate the gene-protein interactions as bone marrow stem cells evolve into mature blood cells. The complete analysis pipeline is documented across multiple Jupyter notebooks, each focusing on a crucial aspect of the data science workflow.

### [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/MJTGhasemi/ScRNA-Sequencing)

### Key Components

#### Data Wrangling
The data wrangling process involved comprehensive data cleaning, integration, and transformation of single-cell genomic data from bone marrow stem cells. This step was crucial for preparing the dataset for in-depth exploratory data analysis and subsequent modeling.

#### Exploratory Data Analysis (EDA)
A thorough EDA was conducted to identify significant patterns, outliers, and relationships within the data. This included univariate, bivariate, and multivariate analyses, utilizing visualization techniques such as heatmaps, violin plots, and scatter plots.

#### Preprocessing and Predictive Modeling
Various machine learning models were developed to predict gene-protein interactions, focusing on model performance and robustness. This phase involved feature engineering, model selection, and extensive evaluation.

### Final Report
The final report compiles all findings and insights, providing a detailed discussion of the methodologies used, key results, implications for future research, and potential practical applications.

### Key Findings
- Identification of critical gene-protein relationships essential for understanding cellular maturation.
- Development of predictive models to forecast cellular differentiation trajectories.
- Insights into potential therapeutic targets and diagnostic markers.

### Technologies Used
- Python
- Jupyter
- Libraries: Pandas, Numpy, Matplotlib, Scikit-Learn, LightGBM

### Implications
The project offers profound insights into cellular biology and provides a foundation for advanced therapeutic strategies and disease understanding, highlighting the importance of integrating computational methods with biological research.

---

## Project Title: **Stock Price EDA and Analysis (Time Series)**

An Exploratory Data Analysis (EDA) and Time Series Analysis have been conducted on stock prices. The data is fetched for four companies: `Apple`, `Google`, `Microsoft`, and `Amazon` from **2018-01-01** to **2023-07-31** using **Yahoo Finance**. By the end of this notebook, we hope to have extracted meaningful insights from our data and built a reliable time series model that can predict future stock prices.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/MJTGhasemi/ML_Projects/tree/main/Stocks%20Analysis)

- The stock data is visualized using line plots and bar plots. These visualizations include volume over time for each company, daily price change, monthly and yearly average closing prices for Apple, pairplots, heatmaps of closing prices and daily returns for all companies, and more.

- The closing prices are transformed to their logarithmic form to stabilize the variance. The data is split into training and testing sets in a chronological manner.

- The Augmented Dickey-Fuller (ADF) test is performed on the training data to check for stationarity. The rolling mean and standard deviation are also plotted.

- Autocorrelation and partial autocorrelation plots are generated for the differences in the closing prices.

- An ARIMA model fits the training data using the auto_arima function, which automatically determines the model's best parameters (p, d, q).

- The trained model is used to forecast the closing prices for the test set. The forecasts are plotted alongside the actual values. The residuals of the model are also plotted, and their statistics are displayed. Root Mean Square Error (RMSE) and Mean Absolute Percentage Error (MAPE) are calculated to evaluate the performance of the model.


