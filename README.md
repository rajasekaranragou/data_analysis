# Customer Segmentation Analysis

This project performs basic **data analysis and preprocessing** on a customer dataset. The objective is to clean, explore, and prepare the data for further machine learning tasks like clustering or classification.

---

## 🔧 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Dataset
- File: `mock_titanic_50_named.csv`
- Assumed structure: `CustomerID`, `Gender`, `Age`, `AnnualIncome`, `SpendingScore`

---

## 🚀 Steps Covered

### 1. Import Libraries
Standard libraries for data manipulation and visualization.

### 2. Load Dataset
CSV file loaded using `pandas.read_csv()`.

### 3. Initial Exploration
- Displaying head of data
- Summary statistics
- Data types and shape

### 4. Data Cleaning
- Checking for missing values
- Checking for duplicates

### 5. Preprocessing
- Renaming columns for clarity
- Encoding gender: Male → 0, Female → 1

### 6. Outlier Detection
- Boxplots for `Age`, `AnnualIncome`, and `SpendingScore`

### 7. Visualization
- Pairplot for feature distribution
- Correlation heatmap

### 8. Feature Scaling
- StandardScaler applied to numerical features
- Concatenated scaled features with original data

### 9. Save Cleaned Data
- Final cleaned and scaled dataset saved as `Cleaned_Mall_Customers.csv`

---

## 📊 Output Example
- Cleaned and scaled dataset ready for modeling or clustering.
- Visual plots for EDA (exploratory data analysis).

---

## 📝 Notes
- `%matplotlib inline` is used for Jupyter Notebooks.
- Make sure the CSV file is present in the same directory.

---

## 🔗 Future Enhancements
- Apply clustering (K-Means, DBSCAN)
- Implement classification or customer segmentation logic
