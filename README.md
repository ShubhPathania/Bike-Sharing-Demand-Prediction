# Bike Sharing Demand Prediction
![29c9632c4ab7640fa4f54e016b22ed85](https://github.com/itsroshan137/Horizontal-Swiper/assets/149718190/0fc2fe1a-aaf6-4171-aa77-b97091d6e409)

# Introduction
This project focuses on predicting bike rental demand in Seoul, South Korea, using machine learning techniques. By accurately forecasting demand, the project aims to optimize resource allocation and service availability, ultimately enhancing user experience and increasing profitability for the bike rental service.

# Problem Statement
The goal of this project is to develop a robust regression model to predict the number of bike rentals at specific times, considering various influencing factors such as weather conditions, time of day, seasonality and holidays. Accurate demand predictions will enable better planning and management of the bike-sharing system, ensuring bikes are available when and where they are needed most.

# 📝 Project Highlights

- **Data Quality Assurance:** Checked for duplicate rows and missing values, ensuring a clean dataset for analysis.
Feature Engineering: Transformed the "Date" column into datetime format and extracted day and month. Encoded categorical features and selected relevant predictors using techniques like VIF.

- **Exploratory Data Analysis (EDA):** Conducted extensive EDA to uncover demand trends and relationships between various factors and bike rentals.

- **Hypothesis Testing:** Validated key hypotheses about the influence of temperature, humidity and holidays on bike rental demand.

- **Model Development:** Implemented and fine-tuned five regression models using Grid Search CV to find the best performing model.

- **Model Evaluation:** Assessed models using metrics such as MSE, MAE, RMSE and R² score to determine accuracy and reliability.

# 🔑 Key Insights

- **Demand Patterns:** Rental demand varies significantly by hour, day, month and season, with peak hours showing the highest demand.

- **Weather Impact:** Temperature, humidity, and other weather-related features have a substantial effect on bike rental counts.

- **Holiday Influence:** There are notable differences in bike rentals between working days and holidays, highlighting the need for different strategies on these days.

- **Feature Importance:** Hour of the day, weather conditions, and functional days emerged as the most critical factors in predicting bike rentals.

- **Optimal Model:** The Random Forest Regression model, with hyperparameter tuning, achieved an R² score of 0.895, indicating its strong predictive performance.

# 📜 Conclusion

This project successfully developed a machine learning model capable of accurately predicting bike rental demand in Seoul, demonstrating its high **predictive accuracy of 89.5%**. By leveraging comprehensive data analysis and advanced modeling techniques, the model provides valuable insights into the factors driving bike rentals. These insights can guide strategic decisions for optimizing bike-sharing operations, improving user satisfaction, and enhancing operational efficiency. Future work will focus on integrating additional data sources and deploying the model for real-time demand forecasting.

# 💾 Project Files Description

**Data:** Contains the datasets used for analysis.

**Analysis:** Includes Google Colab notebook.

**README.md:** Provides an overview of the project.

# 🛠️ Build With:

![image](https://github.com/ShubhPathania/Bike-Sharing-Demand-Prediction/assets/149718190/e689d448-2f9f-49b4-b9f2-5071ae074e78)
![image](https://github.com/ShubhPathania/Bike-Sharing-Demand-Prediction/assets/149718190/9ebacff9-c509-40a1-8934-d0f9e5d9c45a)
![image](https://github.com/ShubhPathania/Bike-Sharing-Demand-Prediction/assets/149718190/1b0244d8-6951-4a39-96a8-79f9d9c563cd)
![image](https://github.com/ShubhPathania/Bike-Sharing-Demand-Prediction/assets/149718190/7927a88c-33a9-4043-9114-1cf2f4c9065f)
![image](https://github.com/ShubhPathania/Bike-Sharing-Demand-Prediction/assets/149718190/4048a336-dde2-432a-8aa8-a82f827eb7da)
![image](https://github.com/ShubhPathania/Bike-Sharing-Demand-Prediction/assets/149718190/147663e0-f428-467a-be15-ed06ca4f1986)
![image](https://github.com/ShubhPathania/Bike-Sharing-Demand-Prediction/assets/149718190/fb4c872b-0202-413b-a888-add348c2087e)
