# A/B Testing: Early Repayment Feature Impact

## 📘 Project Overview
This project simulates and analyzes the impact of an early repayment feature on loan repayment behavior using a synthetic dataset. The goal is to demonstrate how A/B testing can be applied to evaluate product features in a fintech context.

## 📊 Dataset
A synthetic dataset of 1,000 users, with control and treatment groups, including:
- Loan amount
- Loan tenure
- Credit score
- Repayment outcome (paid, late, defaulted)

## 🔧 Tools Used
- Python (pandas, numpy)
- Statistical testing (proportions)
- Visualization (matplotlib, seaborn)

## 🧪 Analysis Goals
- Compare repayment outcomes between control and treatment groups
- Visualize distribution of repayment status
- Test statistical significance of any observed differences

## 📂 Files
- `notebook.ipynb`: Jupyter notebook with full analysis
- `data/synthetic_loan_data.csv`: Synthetic loan-level data for analysis

### ✅ Conclusion

Based on the A/B test results comparing repayment rates between the treatment and control groups:

- The **treatment group**, which had access to the early repayment feature, showed a **higher proportion of on-time repayments** compared to the control group.
- The **z-test produced a p-value < 0.05**, indicating that the observed difference is **statistically significant** and unlikely to have occurred by chance.

This suggests that the early repayment feature may have a **positive impact on repayment behavior**, reducing the risk of default and improving overall loan performance.

---

### 📌 Next Steps
- Monitor repayment behavior over a longer period and across more diverse user segments
- Combine with user-level features (e.g., credit score, tenure) for more granular cohort analysis
- Estimate business impact (e.g., net loss reduction, operational efficiency)


---
*Created by [Chi Ho](https://github.com/phuongchi911) | 
