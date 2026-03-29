Loan Approval Prediction System

## 🎯 Problem Statement
Banks receive thousands of loan applications
daily. Manual review is slow and inconsistent.
This AI model instantly predicts whether a
loan should be approved or rejected!

## 📊 Dataset Details
| Detail | Info |
|--------|------|
| Total Applicants | 1000 |
| Features | 6 (age, salary, experience, etc.) |
| Approved | 107 (10.7%) |
| Rejected | 893 (89.3%) |
| Context | Indian market (₹ amounts) |

## 🤖 Model Details
| Parameter | Value |
|-----------|-------|
| Algorithm | Decision Tree |
| Max Depth | 4 |
| Random State | 42 |
| Test Size | 20% |

## 📈 Results
| Metric | Score |
|--------|-------|
| Accuracy | 97.50% |
| Precision | 98% |
| Recall | 99% |
| F1 Score | 99% |

## 📊 Feature Importance
```
loan amount  ███████████████ 0.3935
experience   ██████████      0.2565
credit score ███████         0.1848
salary       ██████          0.1540
exp_loan                     0.0112
age                          0.0000
```

## 💡 Key Insights
- Loan amount is most important factor
- Age has zero importance in approval
- Only 10.7% loans approved (realistic!)
- Experience matters more than age

## 🛠️ Technologies Used
- Python 3
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

## 🚀 How to Run
1. Open notebook in Google Colab
2. Run all cells (Ctrl + F9)
3. See predictions instantly!

## 🧪 Test Case Example
```python
predict_loan(
    age=40,
    salary=50000,
    experience=10,
    loan_amount=3000000,
    credit_score=700,
    existing_loans=1
)
# Output: ✅ APPROVED (100% confidence)
```

## 💡 Key Learnings
- Strict conditions = lower approval rate
- Better feature engineering = higher accuracy
- Decision Tree shows clear feature importance
- Real banking logic implemented in Python

## 👩‍💻 Author
**Sharmeela S**
AI/ML Intern | SmartED | Bengaluru
[GitHub](https://github.com/ssharmeela)

