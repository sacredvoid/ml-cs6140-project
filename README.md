# Predictive Modeling of Nasdaq Closing Cross Auction Prices

## Overview

This project focuses on implementing and comparing various machine learning algorithms for predicting Nasdaq closing cross auction prices using time series analysis. The project is part of the CS6140 course.

## Project Structure

- `data/`: Contains the dataset used for training and testing
- `models/`: Implementations of different machine learning models
- `utils/`: Utility functions and helper scripts
- `notebooks/`: Jupyter notebooks for data exploration and analysis
- `results_new/`: Output files, visualizations, and model results

## Dataset

The project uses a dataset containing features related to stock market auctions, including:

- Stock ID
- Date ID
- Seconds in bucket
- Imbalance size
- Imbalance buy/sell flag
- Reference price
- Matched size
- Far price
- Near price
- Bid/Ask prices and sizes
- Weighted Average Price (WAP)
- Target variable

## Implemented Models

The following models have been implemented and compared:

1. Linear Regression
2. Decision Tree
3. Random Forest
4. XGBoost
5. CatBoost
6. Neural Network (MLP)
7. ARIMA

## Key Findings

Based on the model comparisons, the following performance order was observed (from best to worst):

1. CatBoost
2. Linear Regression
3. Neural Network (MLP)
4. Random Forest
5. XGBoost
6. Decision Tree
7. ARIMA

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/sacredvoid/ml-cs6140-project.git
   cd ml-cs6140-project
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```
   python main.py
   ```

## Results

The `results_new/` directory contains detailed results for each model, including:
- Best model parameters
- Cross-validation results
- Performance metrics (MAE)
- Visualizations of predictions vs. actual values

## Contributors

- Aakash Mahesha
- Avinash Kasireddy
- Samanvya Tripathi

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Optiver for providing the dataset
- CS6140 course instructors and teaching assistants
