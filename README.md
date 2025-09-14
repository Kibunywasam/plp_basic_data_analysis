#  Iris Dataset Analysis with Python

> A data analysis project exploring the classic Iris dataset using **pandas**, **matplotlib**, and **seaborn** to load, clean, analyze, and visualize patterns in flower measurements.

---

## Assignment Objective

This project demonstrates fundamental data analysis skills by:
- Loading and exploring a real-world dataset (Iris)
- Performing basic statistical analysis
- Creating insightful visualizations
- Applying error handling and data cleaning best practices

The goal is to understand how numerical features (sepal/petal dimensions) vary across species — laying groundwork for classification tasks.

---
##  Dataset Used

- **Source**: Scikit-learn’s built-in `load_iris()` dataset  
- **Description**: Contains 150 samples of iris flowers, with 4 numerical features and 3 species:
  - `sepal length (cm)`
  - `sepal width (cm)`
  - `petal length (cm)`
  - `petal width (cm)`
  - `species`: setosa, versicolor, virginica

No external downloads required — dataset is loaded directly via sklearn.

---

##  Key Tasks Completed

| Task | Description |
|------|-------------|
| **1. Load & Explore** | Loaded data using pandas; checked structure, data types, and missing values. No missing data found. |
| **2. Basic Analysis** | Used `.describe()` for summary stats; computed mean petal length per species — revealed clear distinctions between classes. |
| **3. Visualizations** | Created 4 customized plots: <br> • Line chart (trend of sepal length)<br> • Bar chart (avg petal length by species)<br> • Histogram (distribution of petal width)<br> • Scatter plot (sepal vs petal length by species) |
| **4. Error Handling** | Wrapped file/data operations in `try-except` blocks for robustness. |
| **5. Plot Customization** | Added titles, axis labels, legends, colors, grid lines, and annotations for clarity. |

---

##  Key Findings

- **Petal length and width** are highly discriminative between species — especially distinguishing *setosa* from others.
- *Iris virginica* has the largest average petal dimensions; *setosa* the smallest.
- The scatter plot reveals strong clustering — suggesting these features are excellent for supervised classification (e.g., KNN, SVM).
- All visualizations confirm the dataset's suitability for machine learning tasks.

---

##  Technologies Used

- **Python 3.x**
- **pandas** — Data loading and manipulation
- **matplotlib** — Core plotting library
- **seaborn** — Enhanced styling and aesthetics
- **scikit-learn** — Built-in Iris dataset access
- **Jupyter Notebook** — Interactive development environment

---

