# Customer Behavior Analysis Project

## Project Overview

This project aims to analyze customer behavior and identify factors influencing product usage, activity levels, retention, and churn in a banking dataset. By using data visualization, correlation analysis, and statistical insights, the project provides actionable conclusions to guide decision-making and improve customer retention strategies.

---

## Key Questions Addressed

1. **How do customer demographics (Gender, Age, Geography) correlate with the number of products a customer uses?**  
   - Female customers, on average, use slightly more products than males.  
   - Younger customers (18-35) use the most products, while those aged 50+ use the least.  
   - Customers from Spain use slightly more products, while those from Germany use the least.

2. **Is there a relationship between account balance (Balance) and credit score (CreditScore)?**  
   - No significant relationship exists between account balance and credit score, as shown by a near-zero correlation coefficient.

3. **Does tenure (Tenure) with the bank affect customer activity (IsActiveMember)?**  
   - Tenure does not significantly impact customer activity levels.

4. **What is the impact of salary (EstimatedSalary) and credit card ownership (HasCrCard) on customer retention?**  
   - Higher salary bands show weak influence on churn rates, with higher salaries slightly correlating to increased churn.  
   - Credit card ownership reduces churn likelihood, indicating it positively impacts customer retention.

5. **What factors influence customer churn (Exited)?**  
   - Customers are **less likely to churn** if they:  
     - Are active members.  
     - Reside in France.  
     - Are male.  
     - Own a credit card.  
   - Customers are **more likely to churn** if they:  
     - Are older.  
     - Have a higher account balance.  
     - Reside in Germany.  
   - Other factors showed no significant relationship with churn and are not strong predictors.

---

## Methodology

- **Data Cleaning**: Ensured consistent formatting, handled missing values, and prepared the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Used visualizations (e.g., heatmaps, scatterplots) to identify trends and relationships between variables.
- **Statistical Analysis**: Calculated correlation coefficients to quantify relationships.
- **Insights and Recommendations**: Derived actionable conclusions based on data trends.

---

## Tools and Libraries

- **Programming Language**: Python  
- **Libraries**:
  - `pandas` and `numpy` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
  - `sklearn` for statistical analysis and machine learning techniques.

---

## Results and Recommendations

- Focus retention strategies on younger customers and those in Germany, as they are more likely to churn.
- Promote credit card ownership, as it reduces churn likelihood.
- Develop targeted campaigns for older customers and those with higher balances to improve retention.

---

## How to Use This Project

1. Clone the repository:
   ```bash
   git clone [repository_url]
   cd customer-behavior-analysis
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script to generate visualizations and insights:
   ```bash
   python analysis.py
   ```

---

## Future Work

- Explore non-linear relationships between variables.
- Incorporate machine learning models to predict churn more accurately.
- Use external data sources to enhance analysis.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

Special thanks to the contributors and open-source community for supporting the tools used in this project.
