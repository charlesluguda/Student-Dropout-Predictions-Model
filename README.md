# Student Dropout Predictions Model

## Overview

This project aims to predict student dropout rates and academic success outcomes using linear regression. It leverages the sci-kit-learn library for model development and evaluation, providing a simple yet effective solution for predicting student success.

## Usage

1. **Dataset:**
   - Ensure you have the dataset named "data.csv" in the project directory.
   - The dataset should contain relevant features, with the "Target" column indicating the graduation status.

2. **Dependencies:**
   - Install the required Python libraries:
     ```bash
     pip install pandas numpy scikit-learn
     ```

3. **Running the Script:**
   - Execute the provided Python script:
     ```bash
     python predict_dropout.py
     ```

## Code Structure

- `predict_dropout.py`: The main Python script containing the linear regression model, data preparation, and model evaluation.
- `data.csv`: Sample dataset used for training and testing the model.

## Results

The script outputs the accuracy score of the linear regression model on the test set and displays the corresponding predictions.

## Contribution

Feel free to contribute, open issues, or submit pull requests to enhance the functionality or address any issues.

## License

This project is licensed under the [MIT License](LICENSE).
