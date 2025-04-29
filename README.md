## Dataset Description
We used the Titanic dataset provided by Kaggle, which includes the following files:
- `train.csv`: Main dataset used for analysis
- `test.csv`: Separate test dataset
- `gender_submission.csv`: Sample submission (not used in EDA)

## 📊 EDA Steps Performed

##  Data Loading & Inspection
- Used `pandas` to load and explore the dataset
- Checked data types, missing values, and statistical summaries

##  Univariate Analysis
- Distribution of target variable `Survived`
- Count plots for `Pclass`, `Sex`, `Embarked`
- Histograms for `Age`, `Fare`
- Boxplots to detect outliers

## Bivariate & Multivariate Analysis
- Survival rate comparisons by `Sex`, `Pclass`, and `Embarked`
- Age vs Survival analysis using boxplots
- Pairplot for numeric variables
- Heatmap showing correlation between numeric features

## Handling Missing Data
- Filled missing `Age` with median
- Filled missing

##  Visualizations Used
- `sns.countplot()` for categorical comparisons
- `sns.boxplot()` for age and fare distributions
- `sns.heatmap()` to show correlations
- `sns.pairplot()` for multivariate relationships
- `matplotlib.pyplot` for histograms and custom plots

##  Key Insights

- Women had a significantly higher survival rate than men.
- 1st class passengers were more likely to survive than those in 3rd class.
- Younger passengers and children had better survival odds.
- Passengers with higher fare values tended to survive more.
- Most passengers boarded from port `'S'`, but `'C'` passengers had a higher survival rate.

