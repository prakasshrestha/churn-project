# Customer Churn Prediction — End-to-End ML Project
## 1. Business Understanding
**Customer Churn** = when a customer leaves the service (cancels the subscription).

**Why it matters:**
-Acquiring a new customer is 5–7× more expensive than retaining an existing one.
-A 5% reduction in churn can lead to 25–95% profit increase (Bain & Company).

**Business Objective:**
Identify high‑risk customers so the retention team can give targeted offers and reduce revenue loss.

**ML Objective:** Binary Classification
-Target: Churn (Yes/No)
-Output: churn probability for each customer
-Priority Metric: Recall + ROC‑AUC (not accuracy — because the data is imbalanced!)

**Cost Logic:**
-False Negative (missed churner) → customer leaves → ≈ $1000+ lifetime value loss
-False Positive (wrong alarm) → unnecessary retention offer → ≈ $50 cost
-Since FN is far more expensive → Recall is the top priority!
