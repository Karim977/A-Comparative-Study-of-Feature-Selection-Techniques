# A Comparative Study of Feature Selection Techniques

## Project Overview
This project investigates the impact of various feature selection methods on the performance of machine learning models in the context of big data. By utilizing both PySpark and Sklearn, the study contrasts filter-based, wrapper-based, and embedded-based feature selection techniques—specifically Chi-Square, Principal Component Analysis (PCA), and Decision Tree’s Gini Impurity. The objective is to showcase the advantages of employing big data technologies for feature selection in handling high-dimensional datasets.

## Key Findings
- **Performance Metrics**: The methods were evaluated based on accuracy, precision, recall, F1-score, and the execution time of the feature selection algorithms on a Random Forest model.
- **Execution Efficiency**: PySpark implementations were found to significantly outperform sequential Sklearn approaches in execution time, demonstrating the effectiveness of big data technologies in processing large-scale datasets.
- **Trade-Offs**: A notable trade-off between accuracy and efficiency was observed. For instance, while the Decision Tree’s Gini Impurity method offered high accuracy, it required considerably more execution time compared to the Chi-Square method, which was the fastest in selecting the top 10 features.

## Conclusion
The study provides insights into the advantages and limitations of different feature selection techniques and emphasizes the capabilities of big data technologies in efficiently managing large-scale datasets. It also highlights the importance of feature selection in mitigating the curse of dimensionality in machine learning models.

## Technologies Used
- **PySpark**: For implementing big data solutions in feature selection.
- **Sklearn**: For sequential feature selection implementations.
