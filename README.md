📊 Marketing Campaign A/B Testing Analysis

Python 3.x
Pandas
SciPy
Seaborn
Jupyter


📌 Project Overview
Analyzed a real-world marketing A/B test dataset (588K rows) to determine whether an ad campaign significantly increased user conversions compared to a PSA (Public Service Announcement) control group.

🎯 Business Question
Did showing ads instead of PSAs lead to a statistically significant increase in conversions?

🔍 Key Findings
Ad group conversion rate: 2.55% vs PSA group: 1.79%
Chi-Square test p-value: 0.000001 (well below α = 0.05)
Result: Reject H0 — Ads have a real, statistically significant impact
Best day to run ads: Monday | Best hour: 20:00


📁 Project Structure
data/ · images/ · ab_testing_analysis.ipynb · README.md

▶️ How to Run
pip install -r requirements.txt then open ab_testing_analysis.ipynb in Jupyter
