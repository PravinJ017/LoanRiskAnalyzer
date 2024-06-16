# Loan Risk Analyzer

## Overview

Loan Risk Predictor is a machine learning project designed to predict the risk associated with providing loans to clients based on their financial and personal information. The model classifies applicants into high-risk or low-risk categories, assisting financial institutions in making informed lending decisions.

## Features

- Utilizes a RandomForestClassifier model for risk prediction.
- Preprocesses data including income, age, profession, and location.
- Evaluates model performance using standard classification metrics.
- Predicts loan risk for new applicants based on input data.

## Installation

Clone the repository:
```
git clone https://github.com/your_username/LoanRiskPredictor.git
cd LoanRiskPredictor
```

Install dependencies:
```
pip install -r requirements.txt
```

## Usage

1. **Dataset Preparation**: Ensure your dataset (`loan.csv`) is available in the project directory.

2. **Data Preprocessing**: Handle missing values, encode categorical variables, and scale numerical features to prepare data for model training.

3. **Model Training and Evaluation**: Train the RandomForestClassifier model on preprocessed data. Evaluate model performance using classification metrics like accuracy, precision, recall, and confusion matrix.

4. **Predictions**: Use the trained model to predict loan risk for new applicants based on their financial and personal details.

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with Python, scikit-learn, pandas, and Jupyter Notebook.
- Inspired by real-world challenges in loan risk assessment.

