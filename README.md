# Solana Cryptocurrency Analysis & Price Prediction

## Project Overview
A machine learning analysis of Solana (SOL) cryptocurrency price data, implementing a K-Nearest Neighbours classifier to predict opening prices based on historical market data.

## Methodology

### Data Preparation
- **70/30 Split**: 316 samples for training (70%), 136 samples for testing (30%)
- **Data Cleaning**: Removed non-numerical values and index columns
- **Type Conversion**: Converted float values to integers for KNN compatibility
- **Feature Engineering**: Technical indicators, including moving averages and returns

### Technical Analysis
- **10-Day Moving Average**: Price trend analysis
- **Daily Returns Calculation**: Volatility measurement
- **Interactive Visualisations**: Price trends with moving averages

### Machine Learning Implementation
- **K-Nearest Neighbours Classifier**: For price prediction
- **Feature Set**: High, Low, Close, Volume, Market Capitalisation
- **Target Variable**: Opening price
- **Model Validation**: Proper train-test separation to prevent memorisation

## Key Findings
- **Training Accuracy**: 83.2% on training data
- **Test Accuracy**: 0.7% on unseen data
- **Model Limitations**: Significant overfitting observed, indicating need for improved feature selection or alternative algorithms

## Technical Stack
- **Python** with pandas for data manipulation
- **scikit-learn** for KNN classification
- **matplotlib** for financial visualisations
- **Jupyter Notebook** for interactive analysis
