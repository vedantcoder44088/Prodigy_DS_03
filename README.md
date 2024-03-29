## Prodigy_DS_03

## Overview:
This repository contains the code and analysis performed during my internship project at Prodigy. The notebook `Prodigy_DS_03.ipynb` showcases data analysis and predictive modeling tasks using Python.

## Getting Started:
1. **Clone the Repository**:
   ```
   git clone https://github.com/vedantcoder44088/Prodigy_DS_03.git
   ```

2. **Navigate to the Project Directory**:
   ```
   cd Prodigy_DS_03
   ```

3. **Install Required Libraries**:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. **Download the Dataset**:
   Download the dataset named `bank-additional-full.csv` and place it in the project directory.

## Project Steps:
- **Data Loading and Exploration**: Loaded the dataset into a pandas DataFrame and explored its structure and summary statistics.
- **Data Visualization**: Utilized seaborn to create count plots to visualize the distribution of categorical variables.
- **Data Preprocessing**: Encoded categorical variable `Sex` using LabelEncoder.
- **Outlier Detection**: Applied boxplot and IQR method to detect and handle outliers.
- **Feature Selection**: Identified and dropped highly correlated features (`emp.var.rate`, `euribor3m`, `nr.employed`).
- **Model Training**: Built and evaluated decision tree classifiers using scikit-learn.
- **Model Evaluation**: Evaluated the trained models using accuracy score, confusion matrix, and classification report.
- **Visualization of Decision Trees**: Visualized decision trees using plot_tree function.

## Requirements:
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage:
- Open the Jupyter Notebook `Prodigy_DS_03.ipynb` to view the project documentation and code.
- Execute each cell of the notebook to reproduce the analysis and results.

## License:
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
