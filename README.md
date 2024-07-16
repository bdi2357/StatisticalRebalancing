# StatisticalRebalancing

## Overview
This project introduces a novel rebalancing technique based on probabilistic estimations determined by simple classifiers.

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

  Convergence Handling
To handle convergence issues, the imputation process is monitored with a timer. If the process takes too long, the dataset is split further, and the imputation is retried on smaller subsets. This recursive splitting continues until the imputation completes within the specified time.

Results and Evaluation
Evaluate the imputation methods and rebalancing technique by comparing the distributions, correlations, and model performance before and after imputation. Cross-validation is used to assess the robustness of the methods.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## References
Bordley, R. F., Nguyen, T. T., & Zhang, D. (2010). Learning and overcoming imbalanced performance caused by data bias. Decision Analysis, 7(4), 350-373.
Devi, D., Purusothaman, G., Krishna, S. R., & Nepsha, A. (2018). Handling imbalanced data using auxiliary node data descriptions. Knowledge-Based Systems, 156, 48-62.
Loannou, M., Kokkinakis, G., & Moustakas, K. (2021). SMOTE-D: Synthetic minority over-sampling technique with density factor. Knowledge-Based Systems, 231, 107404.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or suggestions.

## License
This project is licensed under the MIT License.
