# Iris-Flower-Analysis

<img width="1416" height="449" alt="setosa, virginica, setosa" src="https://github.com/user-attachments/assets/61294b4b-b1e9-4bc3-89b1-39ff62608e00" />

## Project Overview

Exploratory data analysis of the Iris flower dataset using Python and pandas, examining relationships between sepal and petal measurements across three Iris species through statistical analysis and data visualization.

This project explores the **Iris Flower dataset**, a classic dataset used to understand exploratory data analysis, data visualization, feature relationships, and introductory classification.

The primary objective was to investigate the characteristics and relationships among the flower measurements and understand how effectively these features distinguish the three Iris species. A simple classification model was included as a baseline modeling exercise rather than as the primary focus of the project.

The Iris Flower dataset has been obtained from [Kaggle](https://www.kaggle.com/datasets/arshid/iris-flower-dataset).

## Objectives

The analysis aimed to:

* Understand the structure and characteristics of the dataset
* Examine the distribution of the numerical measurements
* Compare measurements across Iris species
* Investigate relationships between features
* Identify patterns that may distinguish the three species
* Establish a simple baseline classification model

## Dataset

The dataset contains **150 observations** across three Iris species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

Each observation contains four flower measurements:

* `sepal_length`
* `sepal_width`
* `petal_length`
* `petal_width`

The target variable is `species`.

Each species is represented by **50 observations**, resulting in a balanced dataset.

## Analysis Workflow

The project followed these main stages:

1. Data loading and initial inspection
2. Data structure and data quality assessment
3. Descriptive statistics
4. Exploratory data analysis
5. Feature distribution analysis
6. Species-level comparisons
7. Boxplot analysis
8. Feature correlation analysis
9. Correlation heatmap
10. Feature relationship visualization
11. Baseline classification model
12. Model evaluation

## Exploratory Data Analysis

Several visualizations were used to investigate the dataset, including:

* Histograms of the four flower measurements
* Boxplots comparing measurements across species
* Scatter plots examining relationships between features
* Correlation heatmap

### Key Findings

The analysis revealed clear differences in measurements between the three species.

* **Iris-setosa** showed the clearest separation from the other two species, particularly in petal measurements.
* **Petal length and petal width** showed a strong relationship and were particularly informative for distinguishing species.
* **Iris-versicolor and Iris-virginica** displayed some overlap, indicating that they are more difficult to distinguish based solely on individual measurements.
* The boxplots demonstrated noticeable differences in the distributions of petal measurements across species.
* The balanced representation of the three species allowed comparisons to be made without the results being dominated by a majority class.

## Baseline Classification

A baseline **Logistic Regression** classifier was developed to determine whether the four numerical measurements could predict Iris species.

The model achieved:

**Accuracy: 96%**

The classification performance was strong across all three species:

| Species         | Precision | Recall | F1-score |
| --------------- | --------: | -----: | -------: |
| Iris-setosa     |      1.00 |   1.00 |     1.00 |
| Iris-versicolor |      0.93 |   0.95 |     0.94 |
| Iris-virginica  |      0.95 |   0.93 |     0.94 |

The balanced class distribution and comparable macro and weighted averages indicate that the performance was not driven by a majority class.

The baseline model therefore demonstrated that the four flower measurements contain substantial information for distinguishing the three Iris species.

## Conclusion

The analysis demonstrated that the Iris dataset contains clear and meaningful patterns that can be identified through exploratory data analysis and visualization. In particular, petal measurements provided strong separation between the species, while some overlap remained between Iris-versicolor and Iris-virginica.

A simple Logistic Regression model achieved **96% accuracy** on the evaluated test set, providing a strong baseline for species classification. Since the primary objective of the project was exploratory analysis rather than extensive model optimization, no further hyperparameter tuning or advanced modeling was pursued.

Overall, the project provided practical experience in **data exploration, visualization, statistical interpretation, feature relationships, and introductory multiclass classification**.

## Future Work

Potential extensions to the project include:

* Comparing additional classification algorithms
* Applying cross-validation to assess performance stability
* Investigating feature selection
* Exploring the effect of individual features on classification
* Performing more detailed model interpretation
* Comparing baseline and optimized models

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Author

**Kevin Karanja**

BSc Statistics | Data Science & Analytics
