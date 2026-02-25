# 📊 Sales Analysis Project

## 📌 Project Overview
The Sales Analysis Project is a comprehensive data analytics study conducted on a quarterly sales dataset. The objective is to analyze sales and unit performance trends, identify patterns across months and states, and generate actionable business insights using data visualization and statistical analysis.

This project was implemented using Python in JupyterLab Notebook.

---

## 🎯 Objectives

- Prepare and clean the dataset for analysis
- Normalize sales and unit data
- Analyze overall and monthly trends
- Perform descriptive statistical analysis
- Conduct unit and revenue distribution analysis
- Perform statewise and groupwise analysis
- Explore time-based sales patterns
- Generate visual insights using charts and plots

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- JupyterLab Notebook

---

## 📂 Dataset

**File Used:** `Sales.csv`

The dataset contains:
- Date
- Units Sold
- Sales Revenue
- State information
- Other relevant categorical variables

---

## 🔎 Project Workflow

### 1️⃣ Data Preparation
- Imported necessary libraries
- Loaded dataset into DataFrame (`df`)
- Checked dataset dimensions
- Verified missing values
- Ensured data integrity

### 2️⃣ Data Normalization
- Extracted numerical columns (Units & Sales)
- Applied Min-Max normalization
- Verified scaling between 0 and 1

### 3️⃣ Trend Visualization
- Plotted daily aggregated Units vs Date
- Plotted daily aggregated Sales vs Date

### 4️⃣ Monthly Analysis
- Segmented data into:
  - October
  - November
  - December
- Performed sub-dataframe analysis using `loc`

### 5️⃣ Descriptive Statistics
- Used `describe()` to analyze:
  - Mean
  - Standard deviation
  - Quartiles
  - Min/Max values

### 6️⃣ Unit & Sales Distribution
- Boxplots for monthly unit distribution
- Revenue distribution visualization

### 7️⃣ Consolidated Analysis
- 3-month sales comparison
- Monthly performance trends
- Combined sales plot

### 8️⃣ Statewise Analysis
- Analyzed sales performance by state
- Identified top-performing regions

### 9️⃣ Groupwise Analysis
- Explored categorical performance metrics
- Compared grouped sales performance

### 🔟 Timewise Analysis
- Examined sales patterns across time
- Identified seasonal trends

---

## 📊 Key Insights

- Identified peak sales periods
- Observed seasonal demand fluctuations
- Determined high-performing states
- Detected sales variability across months
- Highlighted revenue growth patterns

---

## 📈 Business Impact

This analysis helps:

- Optimize inventory planning
- Improve marketing campaign timing
- Identify high-revenue regions
- Understand seasonal buying behavior
- Support data-driven decision-making

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/sharmaprabudh/sales-analysis-project.git
   ```

2. Navigate to the project directory:
   ```bash
   cd sales-analysis-project
   ```

3. Open JupyterLab:
   ```bash
   jupyter lab
   ```

4. Open the notebook and run all cells.

---

## 👤 Author

Prabudh Sharma
Data Analyst | Python | Data Visualization
