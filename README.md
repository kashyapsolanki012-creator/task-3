
---

# 🚢 Titanic Survival Analysis (Exploratory Data Analysis)

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the factors that influenced passenger survival. The analysis is done using Python in Jupyter Notebook and includes data visualization, statistical summaries, and correlation analysis.

The dataset used in this project is the famous Titanic dataset available on **Kaggle**.

---

## 📖 Project Overview

The objective of this project is to:

* Analyze survival distribution
* Study survival patterns based on passenger class, gender, age, fare, and family size
* Understand correlations between different features
* Visualize insights using graphs and heatmaps

The notebook performs step-by-step data exploration to identify key survival factors.

---

## 📂 Dataset Information

The project uses two CSV files:

* `train.csv` – Training dataset containing survival labels
* `test.csv` – Testing dataset

Main Features in the Dataset:

* Survived (Target variable)
* Pclass (Passenger class)
* Sex
* Age
* SibSp (Siblings/Spouses aboard)
* Parch (Parents/Children aboard)
* Fare
* Embarked (Port of embarkation)

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 📊 Analysis Performed

### 1️⃣ Dataset Overview

* Dataset shape
* First 5 rows
* Basic information

### 2️⃣ Survival Distribution

* Count of survived vs not survived
* Survival rate percentage
* Bar chart visualization

### 3️⃣ Survival by Passenger Class

* Survival count by class
* Survival rate comparison
* Bar charts

### 4️⃣ Survival by Gender

* Male vs Female survival comparison
* Count and survival rate analysis
* Visualization charts

### 5️⃣ Age Analysis

* Age statistics
* Age distribution by survival
* Histogram comparison

### 6️⃣ Fare Analysis

* Fare statistics
* Fare distribution by survival
* Histogram visualization

### 7️⃣ Family Size Analysis

* Created new feature: `FamilySize`
* Survival rate by family size
* Graphical representation

### 8️⃣ Embarked Port Analysis

* Passenger count by port
* Survival rate by embarkation point
* Bar charts

### 9️⃣ Correlation Analysis

* Encoded categorical variables
* Generated correlation matrix
* Heatmap visualization

---

## ▶️ How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to the folder:

```bash
cd your-repo-name
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `task3.ipynb` and run all cells.

---

## 📈 Key Insights

* Female passengers had a significantly higher survival rate than males.
* Higher-class passengers (Pclass 1) had better survival chances.
* Fare and survival show positive correlation.
* Smaller families had better survival probability.
* Gender is one of the strongest correlated features with survival.

---

## 🚀 Future Improvements

* Handle missing values more formally
* Apply feature engineering
* Build a machine learning prediction model
* Compare multiple classification algorithms

---

