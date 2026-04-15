## Pricing Experiment — First Purchase Discount

Take-home case study analyzing the impact of a first-purchase discount on class pack performance using a Difference-in-Differences (DiD) causal inference approach.
## 📌 Overview

This project evaluates the causal impact of a 15% discount on first-time class pack purchases in a marketplace setting.
The analysis compares Test vs Control groups across Pre and Post periods to isolate the incremental effect of the discount on the funnel.

## 📊 Project Versions

This project includes two versions:

- **Business Impact Analysis**  
  Focused on business insights and decision-making  

- **Econometric Evaluation (Diff-in-Diff)**  
  Focused on causal inference and statistical rigor  

## 🎯 Business Question
Did offering a 15% discount to new users increase demand and improve funnel performance compared to a control group without discount?

🔬 Experimental Structure

Groups:
Test (users exposed to discount)
Control (users not exposed)

Time:
Pre period
Post period

Funnel metrics:
Pack Views
Purchases
Conversion Rate


## 📊 Types of Analysis Performed

### Business Impact Analysis
- Data quality and experiment integrity checks  
- Construction of derived metrics (e.g. conversion rate)  
- Exploratory Data Analysis (EDA)  
- Pre vs Post comparison by group  
- High-level Diff-in-Diff (intuitive interpretation)  
- Segmented analysis by price tier  

### Econometric Evaluation (Diff-in-Diff)
- Data validation and experiment consistency checks  
- Formal construction of treatment and post indicators  
- Baseline comparability tests (Pre-period)  
- Regression-based Diff-in-Diff estimation  
- Clustered standard errors  
- Fixed effects models (company and time)  
- Statistical inference (confidence intervals, p-values)  
- Power analysis (by metric)  

## 🚀 Next Steps

- Improve notebook design and visual presentation (layout, hierarchy, colors)  
- Code improvements and refactoring for readability and reproducibility  
- Create an executive presentation summarizing key insights  
- Add a Q&A section comparing the different methodologies  



