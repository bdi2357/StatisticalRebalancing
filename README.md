# StatisticalRebalancing

## Description
This repository contains the implementation of various imputation techniques and rebalancing strategies for handling imbalanced datasets in binary classification tasks. The focus is on comparing the performance of different imputation methods and evaluating the effectiveness of different rebalancing approaches.

## Key Features
- **Rebalancing Strategies**: Evaluation of resampling techniques (oversampling, undersampling), synthetic data generation (SMOTE, ADASYN), and adjusting class weights.
- **Focused Oversampling**: A novel approach to oversampling that targets instances near decision boundaries for better model performance.
- **Aggressive Oversampling**: Techniques to achieve a more balanced class distribution in highly imbalanced datasets.

## Contents
- **Rebalancing Scripts**: Python scripts for applying various imputation and rebalancing methods.
- **Evaluation Framework**: Scripts for training classifiers on imputed datasets, evaluating their performance, and aggregating results.
- **Sample Data**: Example datasets used for demonstrating the techniques.
- **Results and Analysis**: Comparative analysis of different methods, presented in a structured format.

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/StatisticalRebalancing.git
    ```
2. Navigate to the project directory:
    ```bash
    cd StatisticalRebalancing
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the imputation and rebalancing scripts as described in the documentation.

## Requirements
- Python 3.8+
- Pandas
- Scikit-learn
- Imbalanced-learn
- Fancyimpute
- XGBoost (if using the focused oversampling with XGBoost)

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or suggestions.

## License
This project is licensed under the MIT License.
