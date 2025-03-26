🧠 Project Overview
	•	Course: CSCE 689 – Special Topics in Human-AI Interaction
	•	Title: Bias Detection in AI Algorithms
	•	Focus: Analyzing age and gender bias in employee attrition prediction using a RandomForest classifier
	•	Tools Used: Python, sklearn, calibration curves, error analysis

⸻

📦 Suggested GitHub Repository Name

Choose one of these clean and descriptive names:
	1.	bias-detection-employee-attrition
	2.	human-ai-bias-analysis
	3.	ai-bias-detection-age-gender
	4.	attrition-bias-human-ai
	5.	✅ Recommended: bias-detection-hr-ml (clear, concise, practical)

⸻

📝 README.md File for This Project

# Bias Detection in AI Algorithms: Age & Gender in Employee Attrition Prediction

This project investigates **bias in machine learning models** with respect to **age and gender**, specifically in the context of employee turnover prediction. Developed as part of **CSCE 689: Human-AI Interaction** at **Texas A&M University**, the project evaluates a **Random Forest classifier** for signs of demographic bias using error rate analysis and calibration curves.

---

## 📁 Repository Structure

bias-detection-hr-ml/
│
├── Code/                      # Jupyter notebook with training, predictions & analysis
│   └── CSCE 689 Human AI - Interaction HW- 01 ISHANT KUNDRA.ipynb
│
├── Report/                    # Formal PDF write-up
│   └── CSCE 689 Human-AI Interaction HW- 01 ISHANT KUNDRA.pdf
│
├── Dataset/                   # Dataset used for the project
│   └── Employee.csv
│
└── README.md                  # You’re here!

---

## 📌 Project Objective

To detect **algorithmic bias** in employee attrition prediction models by:
- Examining leave prediction disparity across age and gender groups
- Measuring **Type 1 & Type 2 errors**
- Analyzing **calibration curves** for model trustworthiness

---

## 🧪 Methodology

- Random Forest classifier (`sklearn`)
- 70/30 train-test split
- **Protected Attributes**: Age (`<30`, `>=30`) and Gender (`Male`, `Female`)
- Metrics evaluated:
  - Leave rates
  - Type 1 and Type 2 error rates
  - Calibration curves

---

## 🔍 Key Findings

- **Age Bias**: Higher false positives for younger employees; calibration for older group diverged significantly
- **Gender Bias**: Females had a higher leave rate and poor calibration curve fit
- **Conclusion**: The model, while accurate, displays measurable bias that could lead to unfair or harmful decisions in HR contexts

---

## 📊 Visualizations

- Error rates by group (Age & Gender)
- Calibration curve analysis per subgroup
- Model performance insights

---

## ⚙️ Tools & Libraries

- Python
- Scikit-learn (`sklearn`)
- Matplotlib
- Pandas

---

## 🧠 What You’ll Learn

- How to detect and interpret bias in machine learning predictions
- Importance of subgroup error analysis
- Practical use of calibration curves to validate fairness

---

## 👨‍💻 Author

**Ishant Kundra**  
M.S. Computer Science, Texas A&M University  
📬 [ishantkundra9@gmail.com] 
