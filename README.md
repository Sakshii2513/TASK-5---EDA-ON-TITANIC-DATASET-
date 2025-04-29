
# Titanic Dataset Analysis 🚢

This project explores the [Titanic dataset](https://www.kaggle.com/c/titanic/data) using Python, pandas, seaborn, and matplotlib. It aims to uncover insights into passenger survival rates based on features like age, sex, class, and fare.

## 📁 Files
- `TITANIC_DATASET.ipynb` – Jupyter notebook containing all analysis and visualizations.
- `train.csv` – Original Titanic dataset (from Kaggle).

## 📊 Exploratory Data Analysis (EDA)

### 1. Data Exploration
- Used `.describe()`, `.info()`, `.value_counts()` to understand dataset structure and distributions.
- Identified missing values in `Age`, `Cabin`, and `Embarked`.

### 2. Visualizations
- **Pairplot**: Relationships among `Age`, `Fare`, `Pclass`, `SibSp`, `Parch`.
- **Heatmap**: Correlation between numerical features.
- **Histograms**: Distribution of passenger ages.
- **Boxplots**:
  - Fare distribution across passenger classes.
  - Age distribution for survivors vs non-survivors.
- **Scatterplot**: Age vs Fare, colored by survival status.
- **Countplot**: Gender-wise survival count.

## 🔍 Key Observations
- Females had a much higher survival rate than males.
- Higher passenger class (Pclass = 1) had better survival odds.
- Younger passengers were slightly more likely to survive.
- Fare and Pclass were positively correlated.
- Most passengers embarked from port 'S'.

## ✅ Requirements

- Python 3.x
- pandas
- seaborn
- matplotlib

Install requirements:
```bash
pip install pandas seaborn matplotlib
```

## 📌 How to Run
1. Clone the repo or download the notebook and `train.csv`.
2. Open `TITANIC_DATASET.ipynb` in Jupyter Notebook.
3. Run the cells to see analysis and visualizations.

## 📘 License
This project is open source and free to use for educational or research purposes.
