# Solubility-Prediction
# Predicted vs Actual Log Solubility Analysis

This repository contains a Jupyter Notebook that predicts and analyzes the solubility of compounds using machine learning models. The code focuses on evaluating model performance by comparing predicted log solubility values with actual values.

## Features

1. **Dataset Preparation**: The code loads, preprocesses, and splits the dataset into training and testing sets.
2. **Model Training and Evaluation**: Implements and evaluates a machine learning model to predict log solubility.
3. **Performance Metrics**: Calculates metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) values to measure the model's performance.
4. **Visualization**: Generates scatter plots to visualize the relationship between predicted and actual log solubility values, highlighting the model's accuracy.
5. **Improvement Analysis**: Includes an enhanced model evaluation with optimized parameters.

## Files

- `Code_solubility.ipynb`: The Jupyter Notebook containing the code.
- `predicted_vs_actual_after_improvement.png`: The scatter plot comparing predicted and actual log solubility values after improvement.

## Dependencies

The code is written in Python and requires the following libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

Ensure all dependencies are installed using the following command:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage

1. Clone this repository:

   ```bash
   git clone <(https://github.com/Riyarajput27/Solubility-Prediction/tree/main)>
   ```

2. Navigate to the repository folder:

   ```bash
   cd <(https://github.com/Riyarajput27/Solubility-Prediction/tree/main)>
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Code_solubility.ipynb
   ```

4. Run all cells to execute the code and view the results.

## Results

The analysis provides a scatter plot comparing predicted and actual log solubility values. The plot demonstrates the model's performance and improvements made through optimization.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributions

Contributions are welcome! Please submit issues and pull requests for any improvements or suggestions.

