# Titanic Survival Prediction – Pipeline vs Manual ML Workflow

This project demonstrates why Machine Learning Pipelines are critical in real-world ML systems by comparing:

• Manual ML Workflow (without pipelines)  
• Professional ML Pipeline Workflow (using Scikit-Learn Pipelines)

Instead of focusing only on prediction, this project focuses on engineering quality, reproducibility, and deployability.

---

## Why This Project?

Many beginners train models but fail to build production-ready ML systems.
This project shows:

• How manual ML workflows are risky and unscalable  
• How pipelines solve real industry problems  
• How to build reusable, leak-free ML systems  

---

## Approach Comparison

| Manual Workflow | Pipeline Workflow |
|-----------------|------------------|
| Separate preprocessing steps | Unified Pipeline object |
| Repeated fit/transform calls | Single `.fit()` and `.predict()` |
| Risk of data leakage | Leakage-safe |
| Hard to reuse | Fully reusable |
| Not production friendly | Production ready |

---

## Pipeline Structure

The pipeline includes:

• Missing value imputation  
• Categorical encoding  
• Feature scaling  
• Feature selection  
• Model training  

All inside one reusable object.

---

## Technologies Used

• Python  
• Pandas  
• NumPy  
• Scikit-Learn  
• Jupyter Notebook  
• Git & GitHub  

---

## Key Learning

✔ How pipelines prevent data leakage  
✔ How to build clean ML systems  
✔ How production ML differs from notebook ML  

---

## Conclusion

Professional ML is not about models — it is about systems.
Pipelines convert experiments into deployable ML solutions.
