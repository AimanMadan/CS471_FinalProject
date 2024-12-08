# CS471 Project: Machine Learning Binary Classification of Glioma Grades

This project develops a machine learning model to classify glioma grades into High-Grade Gliomas (HGG) and Low-Grade Gliomas (LGG) using radiomic features derived from MRI scans. Early and accurate classification can significantly improve patient outcomes by guiding treatment strategies more effectively.

## Key Features
- **Dataset**: BraTS 2020 Training Dataset with radiomic features extracted from four MRI sequences (T1, T1CE, T2, and FLAIR).
- **Preprocessing Techniques**:
  - Removal of redundant columns.
  - Standardization and normalization of data.
  - Techniques like Mean Radiomic Features, Concatenated Radiomic Features, and Weighted Radiomic Features.
- **Addressing Class Imbalance**:
  - Data Augmentation and noise addition.
  - Synthetic Minority Oversampling Technique (SMOTE).
  - Class weights for minority class emphasis.
- **Algorithms Used**:
  - Support Vector Classifier (SVC).
  - Decision Tree.
  - Gradient Boosting (achieved the best F1-score: 98%).

## Highlights
The project showcases the integration of advanced preprocessing and machine learning techniques to overcome challenges like class imbalance and feature dimensionality, resulting in a robust model for medical diagnostics.

## Results
- **Best Algorithm**: Gradient Boosting with an F1-score of 98%.
- Effective preprocessing techniques like weighted classes and sequence analysis improved performance and fairness in classification.

## Contributors
- **Aiman Madan**: Data preprocessing, Mean Radiomic Feature method, SMOTE, and augmentation testing.
- **Ken Lopez**: Sequence weights, class weighting, and hyperparameter tuning.
- **Cristian Enriquez**: Algorithm testing, including SVC, Decision Tree, and Gradient Boosting, as well as report contributions.

## References
- BraTS 2020 Dataset: [CBICA BraTS 2020](https://www.med.upenn.edu/cbica/brats2020/data.html)
- Mean Image Transformation Method: [SpringerLink](https://link.springer.com/chapter/10.1007/978-3-031-66535-6_10)

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
