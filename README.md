# E-Commerce Customer Engagement and Behavior Analysis

## 📌 Project Overview

This project focuses on analyzing e-commerce customer data using Python and Exploratory Data Analysis (EDA) to understand customer purchasing behavior, engagement levels, spending patterns, and customer lifetime value.

The main goal is to extract meaningful insights from customer data that can help businesses improve customer satisfaction, retention, and marketing strategies.

## 🎯 Project Objectives

- Analyze customer demographics and purchasing patterns.
- Understand customer engagement across different platforms.
- Identify high-value customers based on Customer Lifetime Value (CLV).
- Analyze average order value across product categories.
- Explore relationships between purchases and customer lifetime value.
- Compare premium and non-premium customer behavior.
- Generate data-driven business insights.

## 🛠️ Technologies Used

- **Python** – Data analysis and manipulation
- **Pandas** – Data cleaning and data processing
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis

## 📂 Dataset Information

The dataset contains **10,000 customer records and 23 columns** covering customer demographics, purchasing activity, engagement, and satisfaction.

Important columns include:

- `CustomerID`
- `Age`, `Gender`, `Country`, `City`
- `IncomeLevel`
- `TotalPurchases`
- `AverageOrderValue`
- `CustomerLifetimeValue`
- `FavoriteCategory`
- `EmailEngagementRate`
- `SocialMediaEngagementRate`
- `MobileAppUsage`
- `AverageSatisfactionScore`
- `RepeatCustomer`
- `PremiumMember`
- `HasReturnedItems`

**Dataset Source:** [E-Commerce Customer Engagement Dataset on Kaggle](https://www.kaggle.com/datasets/noir1112/e-commerce-customer-engagement)

## 🔍 Project Workflow

### 1. Data Understanding
- Inspected dataset structure and column names.
- Used descriptive statistics to understand numerical features.
- Reviewed data types and summary information.

### 2. Data Cleaning
- Identified and handled missing values.
- Checked for duplicate records.
- Standardized categorical values.
- Examined outliers using boxplots and statistical techniques.
- Applied IQR-based outlier capping.

### 3. Data Manipulation
- Selected and filtered data using Pandas.
- Applied `.loc`, `.iloc`, `.at`, `.iat`, and `.query()`.
- Extracted relevant information for analysis.

### 4. Exploratory Data Analysis (EDA)
- **Univariate Analysis:** Studied individual variables using histograms, boxplots, and count plots.
- **Bivariate Analysis:** Examined relationships between two variables using scatter plots, boxplots, and other visualizations.
- **Multivariate Analysis:** Explored relationships among multiple variables using pair plots and correlation heatmaps.

## 📊 Key Findings

- France had the highest customer count among the countries represented in the dataset.
- The average order value was highest for the Sports category.
- France recorded the highest average Customer Lifetime Value among the countries analyzed.
- Total purchases and Customer Lifetime Value showed a moderate positive correlation of approximately **0.437**.
- Age and Customer Lifetime Value had almost no linear correlation in this dataset.
- Premium and non-premium customers had very similar average purchase counts.

## 💡 Business Recommendations

- Develop retention strategies for valuable and repeat customers.
- Use personalized offers to improve customer engagement.
- Investigate popular product categories to support marketing decisions.
- Monitor customer satisfaction and returned-item patterns.
- Use customer behavior insights to improve marketing and purchasing strategies.

## 📁 Project Structure

```text
ecommerce-customer-behavior-analysis/
│
├── Activity.pdf
├── ecommerce_analysis.ipynb
├── ecommerce_customer_engagement.csv
├── requirements.txt
└── README.md
```

*Replace the example notebook and dataset filenames with your actual filenames if they differ.*

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the project notebook and run the cells in order.
5. Ensure the dataset path in the notebook matches the location of your CSV file.

## 🏁 Conclusion

This project demonstrates the use of Python, data cleaning, data manipulation, and exploratory data analysis to understand e-commerce customer behavior. The findings provide insights into purchasing patterns, customer value, and engagement that can support data-driven business decisions.

## 👨‍💻 Author

** Mundru Veda vedya ram**


