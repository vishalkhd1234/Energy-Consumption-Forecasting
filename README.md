# Energy-Consumption-Forecasting
National Energy Transition Strategy using Machine Learning Techniques
Project Overview
This project aims to develop a comprehensive strategy for national energy transition leveraging machine learning techniques for energy use forecasting. By analyzing the current environment, identifying data collection and processing requirements, and implementing relevant machine learning models, we aim to provide accurate energy consumption forecasts that will assist in policy development and secure funding for further advancements.

Project Outline
	1. Business Understanding
		○ Assess the agency's environment and identify potential partners and stakeholders.
		○ Understand stakeholder requirements, including integration difficulties, data challenges, and objectives such as policy development and energy consumption forecasting.
	2. Data Understanding
		○ Collect historical data, time series data, meteorological data, sensory data, and other relevant sources.
		○ Identify key data types that influence energy forecasting, including electricity load consumption, temperature, energy prices, occupancy, and user behavior.
	3. Data Processing
		○ Develop a proof of concept for data architecture to handle scattered and volatile data with extensive parameters.
		○ Ensure the data pipeline can incorporate new data sources and apply aggregation techniques as needed.
	4. Modelling
		○ Select appropriate machine learning models for forecasting:
			§ Multiple Linear Regression for medium and long-term forecasting due to its high accuracy.
			§ XGBoost Algorithm for its versatility and resource efficiency.
			§ Lasso Regression for addressing overfitting in linear models.
	5. Model Evaluation
		○ Evaluate models using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), R² Score, and Mean Absolute Percentage Error (MAPE).
		○ Compare forecasting accuracy across different models to identify the most effective approach.
	6. Implementation
		○ Address challenges related to scattered data, high dimensionality, and model efficiency.
		○ Pursue data partnerships for granular and live data access.
		○ Optimize the data pipeline for scalability and accuracy as data volume increases.
Key Findings
	• Multiple Linear Regression achieved the highest forecasting accuracy at 96.44%.
	• XGBoost and Lasso Regression also performed well, with accuracies of 93.52% and 96.16%, respectively.
Next Steps
	• Secure partnerships with data providers for continuous data inflow.
	• Implement feature selection techniques to enhance model performance.
	• Scale the data pipeline to accommodate increasing data volume and ensure real-time forecasting capabilities.
