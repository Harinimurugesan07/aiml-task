🚢 Titanic Data Cleaning (Task 1)

✅ Steps Performed

1. Loaded the dataset and explored nulls & data types
2. Handled missing values (`Age` - median, `Embarked` - mode)
3. Dropped `Cabin` column due to too many nulls
4. Encoded `Sex` and `Embarked` columns
5. Scaled `Age` and `Fare` using StandardScaler
6. Visualized and removed outliers from `Fare` using Z-score

 Tools Used
- Python (Google Colab)
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn




🔗 Dataset

[Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Task 2 
📂 Dataset Used:

 [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
`cleaned_titanic.csv` (null values handled from Task 1)



 Tools and Libraries Used

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Google Colab

---

 🔍 Steps Performed
1. Summary Statistics
- Generated mean, median, standard deviation, min, and max values using `df.describe()`
- Identified distribution of numerical features

2. Visualizations
- **Histograms** for `Age` and `Fare` distributions
- **Boxplots** to detect outliers in numerical features
- **Bar plots** for `Sex`, `Pclass`, and `Embarked` vs Survival
- **Pairplot** for `Age`, `Fare`, and `Survived`
- **Correlation Matrix** to find relationships between numerical features

3. Patterns, Trends, and Anomalies
- **Patterns**: Most passengers aged 20–40; more males; most from 3rd class
- **Trends**: Higher class and higher fare → higher survival rate; females had higher survival
- **Anomalies**: Passengers with Fare=0; very old passengers; many missing `Cabin` values

4. Feature-Level Inferences
- `Sex`: Females survived more
- `Pclass`: 1st class had higher survival
- `Fare`: High fare = High survival
- `Age`: Most aged 20–40; young children survived more
- `Embarked`: 'C' port had higher survival than 'S' and 'Q'
- `SibSp`, `Parch`: Small families survived better than solo travelers or large families


