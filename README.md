# E-Commerce App-vs-Website-Impact-on-Sales
## Project Overview
This project demonstrates the application of linear regression to analyze and extract actionable insights from a dataset of an imaginary E-commerce business specializing in online clothing sales. The primary objective is to determine whether the company should focus on enhancing their mobile app or website to maximize annual revenue.

## Dataset Description
The dataset represents customer behavior and spending on an E-commerce platform. Key variables include:

- **Average Session Length**: Average duration of in-store style advice sessions.
- **Time on App**: Average time spent on the app in minutes.
- **Time on Website**: Average time spent on the website in minutes.
- **Length of Membership**: Duration of customer membership in years.
- **Yearly Amount Spent**: Total annual expenditure by the customer on the platform.
  
## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn
  
## Analysis Workflow
- Data Preprocessing: Load and inspect the dataset to understand its structure and contents.
- Exploratory Data Analysis (EDA): Visualize the data to identify trends and relationships between features.
- Modeling: Use linear regression to analyze how different factors (time on app/website, session length, membership length) affect yearly spending.
- Evaluation: Assess the model's performance using metrics like MAE, MSE, and RMSE.
- Interpretation: Derive actionable business insights from the model coefficients.

## Key Insights
The length of membership has the strongest correlation with yearly expenditure, indicating that customer loyalty significantly impacts spending.
Time spent on the app correlates more strongly with annual spending compared to time spent on the website.

## Recommendations
Based on the analysis, the company could either improve the website's user experience to increase its contribution to annual revenue or invest more in the mobile app, leveraging its already strong impact on sales.

