#  Megaline Plan Prediction

A classification project to help Megaline, a mobile service provider, recommend the most suitable plan (Smart or Ultra) to its customers based on monthly behavior. The project uses supervised learning techniques to predict plan selection and optimize accuracy.

---

##  Objective

Build a predictive model to determine whether a customer is more likely to use the **Ultra** (1) or **Smart** (0) plan, based on their mobile usage behavior.

---

##  Dataset Description

The dataset contains monthly user activity data:

- `calls` — Number of calls
- `minutes` — Total call duration (in minutes)
- `messages` — Number of text messages
- `mb_used` — Internet data used (in MB)
- `is_ultra` — Target variable (1 = Ultra plan, 0 = Smart plan)

---

##  Project Workflow

1. **Data Preprocessing**
   - Load and explore dataset
   - Check for data quality and balance

2. **Model Development**
   - Split into training, validation, and test sets
   - Train models: Logistic Regression, Decision Tree, Random Forest
   - Tune hyperparameters (tree depth, estimators)

3. **Evaluation**
   - Use accuracy as the performance metric
   - Compare models and validate with test set
   - Confirm accuracy threshold (≥ 0.75)

4. **Sanity Check**
   - Validate consistency of predictions and identify overfitting

---

##  Key Questions Answered

- Can we predict a user’s plan preference from usage behavior?
- Which classification model performs best for this task?
- How does accuracy change with hyperparameter tuning?

---

##  Project Structure

```
megaline-plan-prediction/
│
├── megaline_plan_prediction.ipynb
├── users_behavior.csv
├── requirements.txt
└── README.md
```

---

##  Tools & Libraries Used

- Python
- pandas
- scikit-learn
- Jupyter Notebook

---

##  Status

✔️ Project completed as part of the **TripleTen Bootcamp** – Sprint: *Binary Classification Models*

---

## 📌 Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
