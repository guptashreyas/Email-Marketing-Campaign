# 📧 Email Campaign Analysis

This project analyzes an email marketing campaign dataset to uncover insights and build a predictive model to optimize user engagement — specifically, the click-through rate (CTR).

## 🎯 Objectives

The analysis answers four core business questions:

1. **What percentage of users opened the email and clicked the link?**  
   → We calculate and report open rate and CTR for the campaign.

2. **Can we build a model to improve the way emails are sent to maximize clicks?**  
   → We train classification models (Random Forest and XGBoost) to predict user click behavior and recommend optimized email targeting strategies.

3. **By how much could the model improve CTR? How would we test that?**  
   → We simulate sending emails only to users with high predicted probability of clicking and estimate CTR lift at various probability thresholds.

4. **Are there any interesting performance patterns across user segments?**  
   → We analyze click performance by segments such as age, gender, email version, and send day.

---

## 🧪 Techniques Used

- **Data Cleaning & Feature Engineering** (Pandas, NumPy)
- **Exploratory Data Analysis** (Matplotlib, Seaborn)
- **Machine Learning Models** (Random Forest, XGBoost via Scikit-learn & XGBoost)
- **Model Evaluation** (AUC, Recall, CTR lift simulation)
- **Segmentation Analysis** (Categorical group comparisons with visualizations)

---

## 📊 Key Insights

- The **personalized email version** resulted in significantly higher engagement than the generic version.
- Users aged **25–45** showed the highest CTR.
- Sending emails **mid-week (Tuesday–Thursday)** performed best.
- A model-based targeting strategy can **improve CTR by up to 4–5x** when focusing on users with high predicted probability.

---

## 📁 Files

- `detailed_email_campaign_analysis.ipynb`: Final Jupyter Notebook with full analysis, visualizations, and detailed code comments.
- `merged_email_campaign.csv`: Cleaned and merged dataset used for analysis.
- `README.md`: Project overview and documentation.

---

## 🚀 How to Run

1. Clone the repository or download the notebook and dataset.
2. Run the notebook in a Jupyter environment.
3. Ensure all required Python libraries are installed:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost
    ```

---

## 📬 Contact

Feel free to connect with me if you have questions or want to collaborate!

---
