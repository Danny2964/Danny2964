<!---
Danny2964/Danny2964 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## 👋 Hi, I'm Danny2964

Boston House Price Prediction
This project aims to predict house prices in Boston using various machine-learning models. It explores regression, classification, and clustering techniques on the Boston housing dataset to effectively analyze and categorize house prices.

Dataset Information
Dataset: Boston House Price Data
Source: Kaggle - Boston House Price Data
Number of Rows: 506
Number of Columns: 14
Features: CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT, MEDV
Target Variable: MEDV (Median Value of Owner-Occupied Homes in $1000's)
Models Implemented
Regression Model
Used to predict the continuous values of house prices based on various features.
Classification Model
House prices are categorized into two groups based on the median price. If a house price is above or equal to the median, it is categorized as one group; otherwise, it belongs to another group.
Clustering Model (Optional)
Houses are grouped into clusters to identify patterns in the data.
Steps to Run the Code
Clone this repository or download the .ipynb file.
Open the Boston_House_Price_Prediction.ipynb file in Google Colab or Jupyter Notebook.
Run each cell in the notebook to execute the analysis.
Evaluation Summary
Regression Model: Evaluated using Root Mean Square Error (RMSE) to determine the model's accuracy in predicting house prices.
Classification Model: Evaluated using accuracy score, which shows the model's performance in categorizing the house prices based on the median.
Clustering Model: If implemented, clustering performance can be visually inspected or evaluated using methods like silhouette score.
Summary of Results
The regression model provided insights into the main factors influencing house prices, with metrics indicating its accuracy.
The classification model categorized houses based on price ranges and performed with reasonable accuracy.
(Optional) The clustering analysis helped identify natural groupings in the housing data.
Repository Structure
Boston_House_Price_Prediction.ipynb: The main notebook containing all the code for data loading, processing, model training, and evaluation.
Boston-house-price-data.csv: The dataset used for the analysis.
README.md: Documentation of the project.
Libraries and Tools Used
Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
Google Colab / Jupyter Notebook
Acknowledgments
Dataset: Kaggle provides this dataset.
Tools: The sci-kit-learn library was used to build and evaluate models.


<!---
Danny2964/Danny2964 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
