# Task 7: SVM Classification - Breast Cancer Dataset

## Objective
Build SVM models using both linear and RBF kernels to classify tumors as malignant (M) or benign (B) from medical features.

## Dataset
- Features: radius, texture, area, smoothness, etc.
- Target: Diagnosis (M = Malignant, B = Benign)

## Tools Used
- Scikit-learn
- NumPy, Pandas
- Seaborn & Matplotlib
- PCA for visualization

## Steps Performed
1. Preprocessed data: encoded target, scaled features.
2. Trained linear & RBF kernel SVMs.
3. Tuned hyperparameters using GridSearchCV.
4. Visualized decision boundary using PCA.
5. Evaluated using classification report and cross-validation.

## Sample Results
- Linear SVM Accuracy: ~96%
- RBF SVM Accuracy (after tuning): ~98%
- Cross-validation Accuracy: ~97%

## Visualization
- PCA used to reduce to 2D for plotting SVM decision boundaries.

## Conclusion
SVM with RBF kernel gives better classification performance on this medical dataset after hyperparameter tuning.

OUTPUT

![Screenshot 2025-07-03 145309](https://github.com/user-attachments/assets/9a7a1e71-e02e-4125-a203-5c8765f8ce41)

![Screenshot 2025-07-03 145335](https://github.com/user-attachments/assets/1f710c64-a327-4bd8-a752-5b9e34a743ba)
