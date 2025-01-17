# EDA With Red Wine Data

## Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** using a dataset related to red wine variants of Portuguese "Vinho Verde" wine. The dataset contains physicochemical (input) and sensory (output) variables, enabling tasks such as classification or regression. The main goal is to explore the relationships between variables, detect patterns, and visualize data insights using Python libraries.

---

## Data Set Information
The dataset contains physicochemical inputs and sensory-based output variables. Due to privacy concerns, details like grape types, wine brand, and selling price are not included. This dataset provides opportunities to:

- Test feature selection methods.
- Analyze the class imbalance (e.g., more normal wines than excellent or poor ones).
- Apply outlier detection algorithms to identify excellent or poor wines.

### Attribute Information
#### Input Variables (Physicochemical Tests):
1. Fixed Acidity
2. Volatile Acidity
3. Citric Acid
4. Residual Sugar
5. Chlorides
6. Free Sulfur Dioxide
7. Total Sulfur Dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

#### Output Variable (Sensory Data):
- **Quality**: Score between 0 and 10.

---

## Tasks Performed
1. **Libraries Used:**
   - `matplotlib`
   - `seaborn`
   - `pandas`

2. **Exploratory Data Analysis:**
   - Checking data correlations.
   - Identifying patterns and relationships between variables.

3. **Data Visualization Techniques:**
   - **Heatmap**: Visualizing correlations.
   - **Bar Graph**: Comparing data categories.
   - **Histogram**: Analyzing data distributions.
   - **Pairplot**: Plotting relationships between pairs of variables.
   - **Catplot**: Visualizing categorical data.
   - **Scatterplot**: Analyzing variable relationships.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/aniruddha26/Wine-Quality
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## Acknowledgments
This project is based on publicly available data for educational and exploratory purposes.
