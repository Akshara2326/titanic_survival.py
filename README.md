
# 🚢 Decision Trees and Random Forests on Titanic Survival Prediction

This project uses **Decision Tree** and **Random Forest** classifiers to predict passenger survival on the Titanic based on simple passenger details.

---

## 📊 Dataset

A small manually created dataset with the following features:

- `Survived` — Whether the passenger survived (1 = Yes, 0 = No)
- `Pclass` — Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Sex` — Gender (converted to numerical values)
- `Age` — Passenger’s age (in years)
- `Fare` — Ticket fare (in USD)

---

## 📌 Technologies Used

- Python
- pandas
- scikit-learn

---

## 📈 Workflow

1. Create a small sample Titanic dataset.
2. Convert categorical data (`Sex`) to numerical values using `LabelEncoder`.
3. Define input features `X` and target labels `y`.
4. Split the data into training and testing sets.
5. Train a **Decision Tree Classifier** and a **Random Forest Classifier**.
6. Make predictions and calculate **accuracy scores** for both models.
7. Print and compare the results.

---

## 🚀 How to Run

1. Make sure you have Python installed.
2. Install the required libraries:
```

pip install pandas scikit-learn

```
3. Run the Python file:
```

python titanic\_survival\_prediction.py

```

---

## 📊 Example Output

```

Decision Tree Accuracy:  1.0
Random Forest Accuracy:  1.0
