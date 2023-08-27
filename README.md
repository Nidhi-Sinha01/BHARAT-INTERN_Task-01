# BHARAT-INTERN_Task-01

# House Price Prediction

## Overview

This project is a simple yet effective implementation of a **House Price Prediction** model using **Linear Regression**. The goal of this project is to predict the price of houses based on various features such as square footage, number of bedrooms, number of bathrooms, and more.

The project is implemented as a Jupyter Notebook, making it easy to understand and modify for your own use case or dataset.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (3.x recommended)
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

You can install the required Python libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd house-price-prediction
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook House_Price_Prediction.ipynb
   ```

4. Follow the steps in the notebook to understand and run the code. You can modify the dataset or tweak the model parameters as needed.

## Dataset

The dataset used in this project is stored in the `data` directory. The dataset should have the following columns:

- `sqft`: Square footage of the house.
- `bedrooms`: Number of bedrooms.
- `bathrooms`: Number of bathrooms.
- `floors`: Number of floors.
- `garage`: Number of garage spaces.
- `price`: The target variable - the price of the house.

You can replace this dataset with your own data if needed.

## Model

The machine learning model used in this project is a simple **Linear Regression** model. Linear regression is a straightforward approach for predicting a numerical value based on one or more input features. The model aims to find the best linear relationship between the input features and the target variable (house price).

## Results

After training the model, you can evaluate its performance using various metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). These metrics will help you understand how well the model is performing in predicting house prices.

## License

This project is licensed under the MIT License. Feel free to use and modify the code for your own purposes.

---

Feel free to explore the Jupyter Notebook and experiment with different datasets or models to improve your house price prediction capabilities. If you have any questions or suggestions, please don't hesitate to reach out. Happy coding! 🏡📈
