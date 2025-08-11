# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Objective
Perform an Exploratory Data Analysis (EDA) on the Titanic dataset to uncover insights using statistical summaries and visualizations.

## 🛠 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

## 📂 Dataset
The dataset contains passenger details from the Titanic disaster, including survival status, age, class, fare, and other attributes.

**Key Columns:**
    - 'Survived' → Survival status (0 = No, 1 = Yes)
    - 'Pclass' → Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd)
    - 'Age' → Age in years
    - 'Fare' → Ticket price
    - 'Sex', 'SibSp', 'Parch', 'Embarked' → Passenger demographics & travel details

📊 Steps Performed
    1. Data Exploration
       - '.info()', '.describe()', '.value_counts()' 
       - Checked missing values and data types.
    2. Visualizations
       - Pairplot ('sns.pairplot')
       - Correlation heatmap ('sns.heatmap')
        - Histograms for numerical features
       - Boxplot for Fare by Passenger Class
       - Scatterplot (Age vs Fare, color-coded by survival)
    3. Observations
       - Higher survival rate for 1st class passengers.
       - Fare is positively correlated with survival.
       - Age distribution is right-skewed.
    4. Summary
       - Survival linked with passenger class, fare, and gender.
       - Missing values in 'Age', 'Cabin', and 'Embarked'.

