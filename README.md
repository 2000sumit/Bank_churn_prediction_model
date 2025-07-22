# Customer Churn Prediction - Bank Marketing Dataset

This project uses a machine learning model to predict whether a customer will **subscribe to a term deposit** based on their personal and financial attributes. The project is built using Python and trained on the **Bank Marketing Dataset** using a **Random Forest Classifier**.

---

## 📂 Project Structure
├── Churn_Bank.ipynb # Jupyter Notebook with data processing & model
├── Bank.csv # Dataset used for training the model
└── README.md # Project overview and usage guide


---

## 📌 Problem Statement

A Portuguese bank conducted marketing campaigns via phone calls to sell term deposit subscriptions. This model helps in **predicting customer churn** — whether the customer will say **'yes'** to subscribing or not.

---

## 🛠️ Technologies Used

- Python
- Pandas
- scikit-learn (RandomForestClassifier)
- Jupyter Notebook

---

## 📊 Dataset Info

File: `Bank.csv`

The dataset contains customer attributes such as:

- `job`: Type of job
- `marital`: Marital status
- `education`: Education level
- `loan`: Whether the customer has a loan
- `y`: Target variable — whether the client subscribed (`yes`/`no`)

These features were encoded and used to build the model.

---

## 🚀 How to Run the Project

1. Clone this repository or download the files.
2. Make sure you have Python and Jupyter Notebook installed.
3. Install required libraries:
   ```bash
   pip install pandas scikit-learn
Open Churn_Bank.ipynb in Jupyter Notebook.

Run all cells to preprocess the data, train the model, and test it.

🧠 Model Used
Random Forest Classifier

Model is trained on 80% of the data and tested on the remaining 20%.

Accuracy and classification report are printed after evaluation.

💡 Features
Simple UI-based prediction using input() prompts.

Manual mapping of user input for prediction.

Predicts if a new customer will subscribe to the term deposit.

✍️ Author
Singh Sumit
📫 Email: sumitpratapsingh2000@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/sumit-singh02/
