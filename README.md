# 🧼 Titanic Dataset - Data Preprocessing and EDA

This notebook focuses on the **Exploratory Data Analysis (EDA)** and **data preprocessing** steps required to prepare the Titanic dataset for machine learning modeling. The Titanic dataset is a popular dataset for practicing classification tasks and understanding the importance of data preparation.

---

## 🧠 Objective

To clean and understand the Titanic dataset, engineer relevant features, and prepare the data for use in machine learning models.

---

## 🔧 Tools and Libraries Used

- Python 🐍
- Pandas
- NumPy
- Seaborn & Matplotlib (for visualization)

---

## 📊 Key Steps Performed

1. **Data Loading**
   - Load the dataset into a Pandas DataFrame.
   - View structure, data types, and basic stats.

2. **Exploratory Data Analysis (EDA)**
   - Visualized survival rates across features like `Sex`, `Pclass`, `Embarked`, etc.
   - Checked distribution of numerical and categorical features.
   - Analyzed correlations and missing values.

3. **Data Cleaning**
   - Imputed missing values in `Age`, `Embarked`, and `Cabin`.
   - Removed unnecessary columns like `PassengerId`, `Name`, and `Ticket`.

4. **Feature Engineering**
   - Created `FamilySize`, `IsAlone`, etc.
   - Encoded categorical features (e.g., `Sex`, `Embarked`) using one-hot and label encoding.

5. **Feature Scaling**
   - Applied standardization to numerical features using `StandardScaler`.

---

## 📈 Results

- The dataset is now fully cleaned, transformed, and ready for machine learning models.
- All missing values handled.
- Categorical variables encoded.
- Numerical features scaled.

---

## 👨‍💻 Author

**Manikumar**  
📧 manikumar2972@gmail.com  


