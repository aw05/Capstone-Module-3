# Capstone-Module-3
# *Syarah.com* : Saudi Arabia Used Car Analysis
This project aims to analyze used car prices in a website ***[Syarah.com](https://syarah.com)***. The goal is to develop a machine learning model to predict used car prices based on each cars and give profits for *Syarah.com*, used car owner, and used car buyer.  

# Dataset  
The dataset used for this analysis is the [Saudi Arabia Used Car Dataset](https://www.kaggle.com/datasets/turkibintalib/saudi-arabia-used-cars-dataset) from Kaggle, which contains information of used cars details.

# Analysis
The main analysis performed in this project includes:
* Exploratory data analysis to understand the characteristics of the dataset,
* Data Cleaning to prepare the dataset for modeling,
* Data Preprocessing to prepare get numerical dataset for modeling,
* Building machine learning models to predict the used cars price, and
* Evaluating model performance and selecting the best model.

# Results
The analysis revealed the following insights:
* Feature `Year` and `Engine_Size` have too high correlation with `Price`
* The XGBoost Regressor model have the smallest error of *MAPE* (24%) in predicting used car price. It means if this model used to predict new used car on *Syarah.com* in same range of prices (>=5000), so mean error of predict price is **25%** by actual price.  

# Future Work
Future work can include:
* Fine-tuning the model hyperparameters to improve model performance
