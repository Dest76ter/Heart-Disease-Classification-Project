# Heart Disease Classification using Logistic regression 

## Dataset Overview
- This project focuses on predicting heart disease based on individual health data.
- Features include age, sex, chest pain type, blood pressure, cholesterol level, and more.

## Data Preprocessing
- Checked for and handled missing values: Found missing values in the 'Ca' and 'Thal' columns.
- Replaced missing values with appropriate methods to ensure data quality.

## Data Exploration
- Checked unique values in each column.
- Performed data scaling using Min-Max scaling for specific columns (e.g., 'Grad_Rate', 'Room_Board').

## Data Visualization
- Visualized relationships between different features using scatter plots and histograms.
- Explored the distribution of 'Outstate' and 'Grad_Rate' for private and public colleges.

## Feature Engineering
- Transformed categorical columns ('ChestPain' and 'Thal') into numerical values for model compatibility.
- Mapped 'ChestPain' categories to numeric values.
- Handled missing values in the 'Ca' and 'Thal' columns, ensuring a clean dataset.

## Model Building

- Utilized Logistic Regression, a suitable algorithm for binary classification tasks.
- Split the dataset into training and testing sets.
- Trained the model on the training set.
- Made predictions on the test set.

## Model Evaluation

- Evaluated the model's performance using accuracy metrics.
- Generated a classification report with precision, recall, F1-score, and support values for each class.
- Visualized the model's predictions against the actual values using scatter plots.

## Conclusion

This project showcases the application of Logistic Regression for heart disease prediction based on health attributes. With data preprocessing, visualization, feature engineering, and model building, we can make accurate predictions about the presence of heart disease in individuals.

## Dependencies

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn

## Usage

1. Clone the repository.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Run the provided Jupyter Notebook or Python script to perform heart disease classification.

### Contributions
Contributions to this project are welcome! Feel free to make enhancements, fix issues, or suggest improvements.

**Disclaimer:** This project may include code or concepts inspired by online tutorials and resources, with credit to the original creators.



