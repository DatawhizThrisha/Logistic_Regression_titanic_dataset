# 🚢 Titanic Survival Prediction using Logistic Regression

This project predicts whether a passenger survived the Titanic disaster using a simple and interpretable machine learning model — **Logistic Regression**.

The notebook walks through everything: data cleaning, feature selection, training the model, evaluating results, and even making predictions from real user input.

---

## 📂 What's Inside the Project?

- A Jupyter notebook with all code and steps  
- Dataset preprocessing (cleaning, encoding)  
- Feature selection based on correlation  
- Model training with logistic regression  
- Model evaluation (Accuracy, F1 Score)  
- User input prediction with survival chance  

---

## 📁 Project Structure

```
titanic-logistic-regression/
│
├── titanic_model.ipynb    👉 Main notebook with full code
├── README.md              👉 Project documentation (this file)
└── data/                  👉 Titanic dataset CSV (add your own if needed)
```

---

## 🔧 Features Used for Prediction

The model uses the following features:

- `Pclass` — Passenger class (1st, 2nd, 3rd)
- `Sex` — 0 for Male, 1 for Female
- `Fare` — Ticket price
- `Embarked_S` — 1 if boarded at Southampton, else 0

These were chosen for their relevance and correlation with survival.

---

## 🔍 Model Evaluation

| Metric    | Score  |
|-----------|--------|
| Accuracy  | 77.1%  |
| F1 Score  | 72.5%  |

The model generalizes well and performs consistently on both training and test data.

---

## 🧪 Sample Prediction from User Input

You can enter passenger info and get survival predictions like this:

```text
Pclass: 3
Sex: 1 (Female)
Embarked_S: 1
Fare: 7.6
```

📊 Output:
```
Prediction: ✅ Yes (Survived)
Probability: 56.18%
```

---

## 🌱 What I Learned

- Data preprocessing and feature engineering  
- How to use logistic regression for binary classification  
- Evaluating models with accuracy and F1 score  
- Creating a user interface in code for real-time predictions  

---

## 👩‍💻 About Me

Hi, I'm **Thrisha** 💚  
A passionate and creative AI & Data Science student who loves exploring how models think.  
This project is part of my learning journey, and I'm proud to share it here!

---

## 📸 Screenshot


```markdown
![Model Demo](![Screenshot 2025-07-08 113214](https://github.com/user-attachments/assets/402a7cc6-0571-4f84-8ad9-78fe529f3183)
)

```

---
