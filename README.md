# Box Office Revenue Prediction Using Linear Regression in Machine Learning

## Project Overview
This project focuses on building a predictive model to estimate the box office revenue of movies before their release. Leveraging historical movie datasets, the model uses Linear Regression along with data preprocessing, feature engineering, and visualization to uncover key factors influencing movie revenue. The project also benchmarks Linear Regression against advanced techniques like XGBoost to improve prediction accuracy.

## Features
- Data cleaning and preprocessing to handle missing and inconsistent data
- Feature engineering including encoding categorical data and applying log transformations
- Visualization of distribution and correlation among features
- Model training using Linear Regression and XGBoost regression
- Evaluation of models using Mean Absolute Error (MAE) on training and validation sets
- Insightful analysis on features impacting box office success

## Technologies Used
- Python (NumPy, Pandas)
- Scikit-learn (train_test_split, LabelEncoder, StandardScaler)
- Matplotlib, Seaborn for visualization
- XGBoost for advanced regression modeling

## Getting Started

### Prerequisites
- Python 3.x
- Required packages: numpy, pandas, matplotlib, seaborn, scikit-learn, xgboost

### Installation
1. Clone the repository:
git clone [(https://github.com/bhavyayay/box_office_prediction)]
2. Install dependencies:
3. pip install -r requirements.txt

### Usage
1. Load the dataset (`boxoffice.csv`) into the project directory.
2. Run the preprocessing and model training script.
3. Evaluate model performance and visualize key features.

## Results
- The Linear Regression model provides a baseline accuracy in predicting box office revenue.
- XGBoost regression shows improved accuracy but may exhibit signs of overfitting.
- Key features such as MPAA rating and genre significantly influence revenue predictions.

## Contributing
Contributions are welcome. Please submit pull requests or issues for bug fixes and feature requests.



## References
- Original project inspired and adapted from the GeeksforGeeks tutorial on Box Office Revenue Prediction using Linear Regression.



