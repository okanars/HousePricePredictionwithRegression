## Amsterdam Housing Prices Prediction

### Overview

This project aims to predict the housing prices in Amsterdam by applying various machine learning techniques. The dataset includes several features like the number of rooms, area, and location coordinates, and the target variable is the price of the house.

### Dataset

The dataset is collected from the housing market in Amsterdam, as of August 2021. The columns in the dataset include:

- **Price:** Price of the house
- **Room:** Number of rooms
- **Area:** Area in square meters
- **Lon:** Longitude coordinate
- **Lat:** Latitude coordinate
- **Unnamed:** Index Column
- **Address:** Address of the house
- **Zip:** Zip code

You can access the dataset from Kaggle by clicking [here](https://www.kaggle.com/datasets/thomasnibb/amsterdam-house-price-prediction).
### Data Preprocessing

1. **Data Exploration:** The data is first explored to understand its structure, statistics, and to check for any missing values.
2. **Data Cleaning:** Rows with missing values in the 'Price' column were dropped.
3. **Visualization:** Relationships between various features like 'Room', 'Area', and 'Price' were visualized using scatter plots, box plots, and heatmaps to understand the correlation.
4. **Feature Selection:** Unnecessary features like 'Unnamed', 'Address', and 'Zip' were dropped, and the data was split into training and test sets.

### Model Building and Evaluation

1. **Linear Regression:** A Linear Regression model was trained on the data, and predictions were made on the test set.
2. **Model Evaluation:** The model's performance was evaluated using Mean Squared Error (MSE) and R^2 Score. The obtained values were:
   - Linear Regression MSE: 60958225226.28521
   - R^2 Score: 0.7998106641653243

### Technologies Used

- Python 3
- Pandas for data manipulation
- Seaborn and Matplotlib for data visualization
- Scikit-Learn for model building and evaluation

### Conclusion

The model provides a good R^2 Score, reflecting its capability to capture the variations in the data. The analysis offers valuable insights into the housing prices in Amsterdam and can be further fine-tuned and enhanced using more complex models or feature engineering.
