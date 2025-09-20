# CSV Data Viewer Shiny App

This is an interactive **R Shiny application** for exploring, analyzing, and visualizing CSV datasets. The app also provides clustering and association rule mining features for deeper data insights.

---

## Features

1. **Data View**
   - Upload and view CSV files.
   - Remove duplicates and handle missing values automatically.

2. **Data Summary**
   - Provides structure (`str`) of the dataset.
   - Displays number of duplicated rows and missing values.

3. **Data Analysis**
   - Pie chart for categorical columns like `paymentType`.
   - Bar chart for `total` spending by `age` or `city`.
   - Boxplot to visualize the distribution of numerical columns.

4. **Clustering**
   - K-Means clustering based on selected features (`total` and `age` by default).
   - Interactive scatter plot of clusters.
   - Users can choose the number of clusters (2-4).

5. **Association Rules**
   - Apriori algorithm for mining frequent itemsets.
   - Users can set minimum support and confidence.
   - Outputs discovered rules and details.

---

## Requirements

- R >= 4.5.1
- Packages: `shiny`, `ggplot2`, `dplyr`, `arules`, `readr`

Install required packages with:

```r
install.packages(c("shiny", "ggplot2", "dplyr", "arules", "readr"))
# data-science
