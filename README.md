# Linear Regression Project

This repository contains examples of Linear Regression implemented both from scratch and using the Scikit-Learn library. It includes interactive visualizations and a web application.

## Project Structure

- **`main.py`**: A Streamlit web application that predicts house prices based on house size. It generates synthetic data, trains a Linear Regression model using Scikit-Learn, and visualizes the results with Plotly.
- **`regression_1.ipynb`**: A Jupyter Notebook demonstrating Linear Regression implemented from scratch. It uses Gradient Descent to optimize the model parameters on the `Salary_Data.csv` dataset.
- **`regression_2.ipynb`**: A Jupyter Notebook demonstrating Linear Regression using the `scikit-learn` library on the `Salary_Data.csv` dataset. It compares the results and provides visualizations.
- **`Salary_Data.csv`**: The dataset used in the Jupyter Notebooks, containing years of experience and corresponding salary data.

## Features

- **From Scratch Implementation**: Understand the mathematics behind Linear Regression by exploring the gradient descent algorithm in `regression_1.ipynb`.
- **Scikit-Learn Implementation**: See how to efficiently implement Linear Regression using industry-standard libraries in `regression_2.ipynb`.
- **Interactive Web App**: Use `main.py` to interact with a trained model, input your own data, and see real-time predictions and visualizations.

## Installation

To run the code in this repository, you need to install the following Python libraries:

```bash
uv init
uv venv
uv add install numpy pandas matplotlib plotly scikit-learn streamlit
```

## Usage

### Running the Streamlit App

To run the House Price Prediction app, execute the following command in your terminal:

```bash
streamlit run main.py
```

This will open a new tab in your web browser where you can interact with the application.

### Running the Notebooks

You can run the Jupyter Notebooks using Jupyter Lab or Jupyter Notebook:

```bash
jupyter notebook regression_1.ipynb
# or
jupyter notebook regression_2.ipynb
```

## License

This project is open-source and available for educational purposes.
