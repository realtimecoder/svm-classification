# Support Vector Machine (SVM) Classification

## Project Overview

This project demonstrates the implementation of Support Vector Machine (SVM) for classification using both Linear and Radial Basis Function (RBF) kernels. The performance of both kernels is evaluated and compared using accuracy scores, confusion matrices, and classification reports.

## Objective

* Implement SVM classification.
* Understand hyperplanes and margins.
* Compare Linear and RBF kernels.
* Evaluate model performance using confusion matrices and accuracy metrics.

## Tools & Technologies

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Dataset

Breast Cancer Wisconsin Dataset (Scikit-learn)

### Features

* 30 numerical features
* Binary classification target:

  * Malignant
  * Benign

## Methodology

1. Load and explore the dataset.
2. Split data into training and testing sets.
3. Standardize features using StandardScaler.
4. Train SVM with:

   * Linear Kernel
   * RBF Kernel
5. Make predictions on test data.
6. Evaluate performance using:

   * Accuracy Score
   * Confusion Matrix
   * Classification Report
7. Compare kernel performances.

## Results

### Linear Kernel

* Trained successfully on standardized data.
* Generated predictions and confusion matrix.
* Achieved high classification accuracy.

### RBF Kernel

* Captured non-linear patterns effectively.
* Produced accurate predictions.
* Achieved competitive performance compared to the Linear kernel.

## Kernel Comparison

| Kernel | Performance                                       |
| ------ | ------------------------------------------------- |
| Linear | Fast and interpretable                            |
| RBF    | Better for complex non-linear decision boundaries |

## Deliverables

* SVM Classification Model
* Linear Kernel Implementation
* RBF Kernel Implementation
* Confusion Matrix Visualization
* Kernel Comparison Report

## Conclusion

Support Vector Machine is an effective supervised learning algorithm for classification tasks. Both Linear and RBF kernels performed well on the dataset. The Linear kernel provided a simpler decision boundary, while the RBF kernel handled non-linear relationships more effectively. The comparison highlights the importance of selecting an appropriate kernel based on data characteristics.

## Author

Sakshi Verma
B.Tech Computer Science
Delhi Technological University (DTU)
