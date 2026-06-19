
This lab demonstrates **feature selection techniques** using Sequential Feature Selection (SFS) with Logistic Regression. The objective is to compare model performance before and after selecting important features using both **forward selection** and **backward selection** methods.

## Dataset

* **File:** `wrapper_dataset_5000.csv`
* The dataset contains multiple input features and a target variable used for classification.

## Libraries Used

* Pandas
* Scikit-learn

## Topics Covered

* Data loading and inspection
* Train-test split
* Logistic Regression model
* Pipeline creation
* Sequential Feature Selection (SFS)
* Forward Selection
* Backward Selection
* Cross-validation
* Model accuracy comparison

## Workflow

1. Load the dataset.
2. Explore the dataset using `head()`, `info()`, and `describe()`.
3. Separate features and target variable.
4. Split the data into training and testing sets.
5. Create a Logistic Regression pipeline.
6. Apply Forward Sequential Feature Selection.
7. Apply Backward Sequential Feature Selection.
8. Evaluate the model using cross-validation accuracy.
9. Compare baseline accuracy with the accuracies obtained after feature selection.

## Techniques Implemented

### Forward Feature Selection

Starts with no features and progressively adds the most significant features to improve model performance.

### Backward Feature Selection

Starts with all features and iteratively removes the least important features while maintaining model performance.

## Results

The notebook compares:

* Baseline model accuracy
* Selected features from forward selection
* Accuracy after forward selection
* Selected features from backward selection
* Accuracy after backward selection

## Tools and Technologies

* Python
* Jupyter Notebook
* Pandas
* Scikit-learn

## File Structure

```
EDA.LAB8.ipynb
wrapper_dataset_5000.csv
README.md
```

## Conclusion

Sequential Feature Selection helps identify the most relevant features for classification tasks. Both forward and backward selection methods are evaluated to determine their impact on model accuracy and feature reduction.

