# Retail-Sales-Prediction-Regression

This repository presents a project titled "Retail Sales Prediction" led by Shubham Singh. The aim of this project is to accurately forecast sales for the company Rossmann. It involves the utilization of the Rossmann dataset and the store dataset, employing various regression techniques such as linear regression, LARS regression lasso, and decision tree. Additionally, cross-validation using GridSearchCV and hyperparameter tuning are incorporated to enhance the performance of the models. The main objective is to provide precise sales predictions, enabling Rossmann to make well-informed business decisions and optimize their operations effectively.

## Dataset Description

The project utilizes two main datasets:

- **Rossmann Stores Data.csv**: This dataset contains historical sales data, including the target variable, "Sales".
- **store.csv**: This dataset provides supplementary information about the stores.

The datasets consist of several fields, including unique identifiers, sales figures, customer data, store information, and promotional activities. Detailed descriptions of the fields can be found in the repository.

## Data Cleaning

Data cleaning is an essential step before conducting exploratory data analysis (EDA), as it eliminates ambiguous data that could potentially impact the analysis. The data cleaning process includes removing duplicate rows, handling missing values, converting columns to appropriate data types, and adding important columns for analysis.

## Key Libraries

The project utilizes various Python libraries for exploratory analysis, including but not limited to:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly

These libraries provide powerful tools and functions for data manipulation, visualization, and model building.

## Machine Learning Models and Techniques

The project employs several machine learning models and techniques for sales prediction:

- Linear Regression
- LARS Regression (Lasso)
- Decision Tree
- Cross Validation using GridSearchCV
- Hyperparameter Tuning

These models and techniques enable the project to make accurate sales predictions based on the available data.
![image](https://github.com/Shubhu1111/Retail-Sales-Prediction-Regression/assets/125637046/40164548-d7b3-49f4-bf3e-2533548f7e7d)
![image](https://github.com/Shubhu1111/Retail-Sales-Prediction-Regression/assets/125637046/3eff20c7-63ea-4c30-8e0b-17238fc40e97)
![image](https://github.com/Shubhu1111/Retail-Sales-Prediction-Regression/assets/125637046/12b892aa-ad8e-49ce-90b6-b70c5b6793f3)


## Conclusion

Based on the analysis, it is observed that the influence of Promo2 on sales is relatively insignificant. However, promotions consistently lead to higher sales and increased customer footfall across all store types. Among the different store types, Type D exhibits the highest average cart size, while Type B tends to have lower average sales per customer, indicating a preference for smaller purchases. The analysis also highlights a notable surge in sales during Christmas week, potentially attributed to heightened consumer interest in beauty products during the holiday season. Moreover, there is a greater prevalence of open stores during school holidays compared to state holidays. Key factors impacting sales include the number of customers, competition distance, store type (StoreType_d), and promotional activities (Promo), which have shown significant significance in determining sales outcomes.

The best performing Decision Tree model, obtained through cross-validation and hyperparameter tuning, achieved an average CV RMSE score of 848.79 and a best model RMSE score of 749.02. It demonstrated favorable training and testing RMSE values of 448.92 and 718.55, respectively, along with a training MAPE of 4.20 and a testing MAPE of 6.83. These results highlight the accuracy and effectiveness of the sales prediction models implemented in this project.
