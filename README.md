# Energy-Consumption-Forecasting
This project focuses on forecasting energy consumption using time series analysis and machine learning techniques. By leveraging historical energy usage data, the model predicts future trends, aiding in optimizing energy distribution and planning. The primary model used is XGBoost
## Features
* Time series forecasting using XGBoost
* Data preprocessing and feature engineering with Pandas & NumPy
* Visualizations for insights and trends using Seaborn & Matplotlib
* Model evaluation using Mean Squared Error (MSE)
## Download Dataset
This project uses the Hourly Energy Consumption dataset from Kaggle. To download it, follow these steps:
1. Obtain your Kaggle API credentials:
  * Go to your Kaggle account settings.
  * Scroll down to the API section and click "Create New API Token" to download kaggle.json.
2. Run the following command in the notebook to download the dataset:
```
import opendatasets as od
od.download("https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption")
```
## Models & Techniques
* Training and testing model in different cases, including lag features
* XGBoost Regressor for time series forecasting
* Feature engineering and preprocessing with Pandas & NumPy
* Performance evaluation using Mean Squared Error (MSE)
##Results & Visualization
The notebook includes visualizations of energy trends and model performance metrics, such as MSE and prediction plots.

![image](https://github.com/user-attachments/assets/61e8aec3-5ef0-4bc5-81b6-855784826a3f)
![image](https://github.com/user-attachments/assets/ac890b7c-b6ed-496f-a5a9-ab64f61e6c4d)
![image](https://github.com/user-attachments/assets/5e01d9d9-2df0-41b1-a7f1-3339f8656ee3)
![image](https://github.com/user-attachments/assets/d6f650c8-3d8c-4094-b72e-7d98d3d32994)

## Contributing
Contributions are welcome! Feel free to fork the repository, submit pull requests, or raise issues.
## License
This project is licensed under the MIT License.
