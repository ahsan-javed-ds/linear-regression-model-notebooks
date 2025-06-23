# Linear Regression Model Projects

Welcome to the **Linear Regression Projects** repository!

This repository is a growing collection of practical implementations of **Linear Regression models** using different real-world datasets. Each notebook is carefully structured to provide clear insights into the data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and performance evaluation processes.

## 📌 Purpose

The primary goal of this repository is to serve as a resource for:

- Understanding how Linear Regression works on various types of datasets.
- Applying data science workflows from data loading to model evaluation.
- Exploring practical examples and enhancing your machine learning portfolio.

---

## 📂 Current Notebooks

# 🚲 Notebook #1: Seoul Bike Sharing Demand Prediction

**Predicting the pulse of Seoul's cycling habits with Linear Regression!**

This repository contains a comprehensive Jupyter Notebook (`linear_regression_seoul_bike_rented_data_ahsan_javed.ipynb`) that dives deep into predicting bike rental demand in Seoul using a Linear Regression model. From data exploration to model deployment, this project covers the end-to-end machine learning pipeline.

## 🌟 Features

* **Exploratory Data Analysis (EDA):** Uncovers the patterns in Seoul's bike rental data, including the impact of weather, time of day, and seasons.
* **Feature Engineering:** Transforms raw data into meaningful features, handling categorical variables and extracting temporal insights (e.g., month, day of week).
* **Linear Regression Model:** Builds and trains a robust Linear Regression model to predict `Rented Bike Count`.
* **Model Evaluation:** Assessment of the trained model's performance using key metrics such as MAE, MSE, RMSE, and R-squared.
* **Model Persistence:** Learn how to save and load your trained model for future use or deployment.

## 🚀 Getting Started

To run this notebook and explore the analysis yourself:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ahsan-javed-ds/linear-regression-model-notebooks.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    cd linear-regression-model-notebooks
    ```
2.  **Download the Dataset:**
    The dataset `SeoulBikeData.csv` is usually available from the [UCI Machine Learning Repository - Seoul Bike Sharing Demand](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand). Place it in the root directory of this repository.
    *(Alternatively, if you've already uploaded `SeoulBikeData.csv` to your environment, you can skip this step.)*
3.  **Create a Conda Environment (Recommended):**
    ```bash
    conda create -n bike_demand python=3.9
    conda activate bike_demand
    ```
4.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
5.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    This will open the Jupyter interface in your browser. Navigate to and open `linear_regression_seoul_bike_rented_data_ahsan_javed.ipynb`.
6.  **Run the Notebook:** Execute the cells sequentially to see the full analysis, model training, and evaluation.

## 📊 Key Insights from EDA

* Bike rentals peak significantly during morning and evening rush hours.
* Temperature and solar radiation show a strong positive correlation with bike demand.
* Rainfall and snowfall are, predictably, negatively correlated with rentals.
* Summer and Autumn seasons see the highest demand, while winter naturally has the lowest.
* `Functioning Day` status is a critical predictor for bike availability and demand.

## 📈 Model Performance

The Linear Regression model achieved a **R-squared ($R^2$) of approximately 0.58**, indicating that 57% of the variance in bike rental count can be explained by the features.

* **Mean Absolute Error (MAE):** ~316 bikes
* **Root Mean Squared Error (RMSE):** ~422 bikes

The model coefficients reveal the most influential factors:
* `Functioning Day` is the most impactful feature.
* `Temperature (C)` and `Hour` are strong positive drivers.
* `Seasons` and `Months` play a significant role, reflecting seasonal and monthly variations.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Upcoming Additions

More notebooks will be added soon, each exploring linear regression with a different dataset and use case, such as:

- House price prediction  
- Advertising & sales data  
- Student performance analysis  
- Startup profit prediction  
- and more...

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy, scikit-learn, matplotlib, seaborn)  
- **Jupyter Notebook** / **Google Colab**
- **Linear Regression** (statsmodels & scikit-learn)
- **Data Visualization**


## 📧 Contact

**Author:** Ahsan Javed
* **Email:** ahsan.javed1702@gmail.com
* **GitHub:** [https://github.com/ahsan-javed-ds](https://github.com/ahsan-javed-ds)
* **LinkedIn:** [https://www.linkedin.com/in/ahsan-javed17/](https://www.linkedin.com/in/ahsan-javed17/)
