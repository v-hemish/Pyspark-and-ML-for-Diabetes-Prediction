# PySpark Diabetes Prediction Analysis

![Diabetes Visualization]([assets/img/project/diabetes_pred.jpg](https://tse2.mm.bing.net/th?id=OIP.ORCMGgpKJA8ib5I59ts5wQHaD4&pid=Api&P=0&h=220))

## Contents

- [About the Project](#about-the-project)
- [Tools & Frameworks](#tools-&-frameworks)
- [Highlight Features](#highlight-features)
- [Achievements & Statistics](#achievements-&-statistics)
- [How to Use](#how-to-use)
- [Credits & References](#credits-&-references)

## About the Project

This endeavor focuses on forecasting diabetes using the Pima Indians Diabetes dataset. In-depth data exploration and strategic feature crafting were instrumental in refining the predictive accuracy.

## Tools & Frameworks

- **PySpark:** Main platform for data manipulation and machine learning tasks.
- **Optuna:** Leveraged for fine-tuning model hyperparameters.
- **Seaborn & Matplotlib:** Employed for graphical data insights.

## Highlight Features

- **In-depth EDA:** Comprehensive analysis of the dataset, showcasing relationships and feature patterns.
- **Feature Refinement:** Introduced feature combinations to elevate model effectiveness.
- **Model Development:** Integrated Logistic Regression and Gradient Boosted Trees via PySpark's MLlib.
- **Enhancements:** Utilized Optuna for systematic hyperparameter adjustments, leading to optimal outcomes.

## Achievements & Statistics

- Completed **10** tuning iterations with Optuna.
- The most successful iteration recorded an accuracy of **95.88%**, using the parameters:
  - maxDepth: 6
  - maxBins: 21
  - maxIter: 13
- The Gradient-Boosted Trees Classifier (with Cross-Validation) registered an accuracy rate of **96.03%**.

## How to Use

1. Download the project repository to your computer.
2. Install all required packages and libraries.
3. Execute the provided PySpark notebook.
4. Ensure Seaborn and Matplotlib are ready for visual outputs.

## Credits & References

- Data sourced from [UCI's Machine Learning Archive](https://archive.ics.uci.edu/ml/index.php).
- A nod to OpenAI and its vast community for continuous insights and feedback.
