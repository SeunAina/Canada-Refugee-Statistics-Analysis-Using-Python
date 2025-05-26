# 📊 Canada Refugee Statistics Analysis

This project analyzes refugee immigration trends in Canada using historical data. 
It focuses on identifying patterns over time, highlighting the top contributing countries, and presenting findings with clear visualizations.

---

## My Approach

### 1.Imported Libraries & Setup
I began by importing:
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib.pyplot` and `seaborn` for plotting

I also defined a helper function `addlabels()` to add value labels on bar plots.

---

### 2.  Data Loading & Exploration
- Loaded the dataset from a CSV file into a pandas DataFrame.
- Inspected the structure using `.head()` and `.info()` to understand its shape and contents.
- Renamed the "OdName" column to `"Country"` for clarity.


### 3. 🧹 Data Cleaning
- Dropped unnecessary columns: `Type`, `Coverage`, and `AREA`.
- Checked for missing values using `.isnull().sum()` — there were none.
- Ensured all column names (especially years) were converted from strings to integers using:
  ```python


---
 ### 4.  Exploratory Data Analysis. Insights and Recommendations
---
