# Exploring and Visualizing a Iris Dataset

## Dataset Used
- **Dataset:** Iris Dataset
- **Source:** Available via the `seaborn` library (`sns.load_dataset("iris")`)
- **Description:** The Iris dataset contains measurements of sepal and petal length and width for three different species of iris flowers (`setosa`, `versicolor`, and `virginica`).

---

## Methods and Visualizations Applied

1. **Data Loading and Inspection**
   - Used `pandas` and `seaborn` to load the dataset.
   - Displayed the shape, columns, and first few rows.
   - Checked for missing values and data types using `.info()` and `.describe()`.

2. **Visual Exploratory Analysis**
   - **Scatter Plots (Pairplot):** To observe relationships between numeric features and distinguish species visually.
   - **Histograms:** To inspect the distribution of each feature.
   - **Box Plots:** To detect outliers and visualize feature spread and central tendency.

---

## Key Results and Findings

- The dataset contains **150 rows** and **5 columns** (4 numeric features + 1 target label).
- No missing values were found; data types are appropriate for analysis.
- Pairplot analysis showed that petal length and width clearly differentiate the three species.
- Histograms revealed that sepal and petal dimensions have relatively distinct distributions.
- Box plots identified some potential outliers, like in sepal width.

---

## Libraries Used

- `pandas`
- `seaborn`
- `matplotlib`

---

