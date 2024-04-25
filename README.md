Overview
This project aims to analyze historical weather data and predict future weather conditions using machine learning techniques. The dataset used contains information about relative humidity (RH), average temperature (TAvg), and maximum temperature (TMax) up to the year 2018.
Files
•	model predictions.ipynb:  Python script containing code for data analysis, outlier detection, model training, and prediction.
•	requirements.txt: File listing required Python packages for running the code.
Usage
1.	The model predictions.ipynb script reads weather data from a CSV file (till2018_final_wh.csv), performs data analysis, detects and removes outliers, trains machine learning models (Linear Regression and Random Forest Regression), and evaluates the models.
2.	Upon execution, the script displays various plots showing the distribution of weather variables, boxplots before and after outlier removal, and comparison between actual and predicted values.
3.	Users can modify input data or add new data for prediction by editing the code or providing input data arrays.
Dependencies
•	matplotlib (v3.4.0): For data visualization and plotting.
•	numpy (v1.20.1): For numerical computing and array operations.
•	pandas (v1.2.3): For data manipulation and analysis.
•	scikit-learn (v0.24.1): For machine learning algorithms and model evaluation.
•	seaborn (v0.11.1): For statistical data visualization.
•	tensorflow (v2.5.0): For building and training neural network models.
________________________________________
This documentation provides an overview of the project, setup instructions, usage guidelines, and dependencies. Users can follow the instructions to analyze weather data, train predictive models, and make forecasts based on the provided dataset or additional data.


