#Objective:
The project aims to analyze various economic factors influencing home prices in the United States over the past years, utilizing a dataset encompassing multiple key indicators.

Data Collection and Preparation:
Multiple datasets were sourced, covering factors such as GDP, Consumer Price Index, Population Growth, Construction Spending, Inflation, Median Household Income, Monthly New House Supply, Unemployment Rate, Working Population, and the House Price Index (HPI).
After importing the datasets, data cleaning was conducted:
Null values in specific columns were handled using techniques such as linear interpolation or mean value substitution.
The data types were standardized, converting object types to float for consistency in further analysis.
Correlation analysis was performed to understand relationships among the variables, visualized via a heatmap.

Exploratory Data Analysis:

Population Growth Analysis:
Analyzed population growth trends over time.
Investigated its impact on the House Price Index.

Modeling and Predictive Analysis:
Split the dataset into independent variables (features) and the target variable (House Price Index).
Scaled and preprocessed the data for machine learning models, applying MinMaxScaler.
Employed various regression models:
Linear Regression, Ridge Regression, and Lasso Regression.
Calculated evaluation metrics including R-squared, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

Results and Insights:
Linear Regression provided an R-squared score indicating the model's explanatory power.
Ridge and Lasso Regression showcased how regularization techniques affect predictive performance.
Visualization of house price trends concerning economic factors such as GDP, Consumer Price Index, Inflation, and Median Household Income.

Conclusion:
The analysis explored and quantified the relationships between economic indicators and home prices.
Insights gained from this analysis could assist policymakers, investors, and individuals in understanding the driving forces behind changes in home prices.

Future Scope:
Further feature engineering or incorporating additional external datasets could enhance model accuracy.
Time-series forecasting models might be explored to predict future home prices based on the identified influential factors.
