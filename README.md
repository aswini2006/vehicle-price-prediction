# Vehicle Price Prediction

This project predicts vehicle prices based on various specifications such as make, model, year, mileage, fuel type, transmission, body type, and more. It uses a Random Forest Regressor for modeling.

## Dataset
The dataset contains detailed specifications of vehicles and their prices, including:
- Make and Model
- Year
- Mileage
- Fuel Type
- Transmission
- Trim
- Exterior and Interior Colors
- Drivetrain
- Price (Target Variable)

> Dataset path in the code: `/kaggle/input/vehicle-dataset/vehicle dataset.csv`

## Project Steps
1. **Data Loading**: Load CSV data into a pandas DataFrame.
2. **Data Cleaning**:
   - Dropped text-heavy columns: `name`, `description`, `engine`
   - Dropped rows with missing values
   - Categorical columns encoded as numerical
3. **Feature Scaling**: Used `StandardScaler` to normalize features.
4. **Model Training**: Random Forest Regressor trained on the dataset.
5. **Model Evaluation**:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score
6. **Visualization**: Feature importance plot using Seaborn.

## Results
The model performance metrics are printed:
- MAE
- RMSE
- R² Score

## Dependencies
Install dependencies listed in `requirements.txt`.

## How to Run
1. Clone or download the project.
2. Run the notebook or Python script in a Jupyter environment (e.g., Kaggle).
3. Make sure the dataset is accessible at the provided path.


**License**: MIT
