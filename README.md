# 🧠 Comment Toxicity Detection

This project uses a deep learning model to detect **toxic comments** in text data. The dataset originates from the [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge), and the model predicts probabilities for multiple categories of toxicity.

---

## 📊 Model Objective

The goal is to classify each comment into one or more of the following categories:
- ☣️ toxic
- 👎 severe_toxic
- 🤬 obscene
- 🚫 threat
- 💥 insult
- 😤 identity_hate

---

## 🧪 Key Features in the Notebook

- ✅ Exploratory Data Analysis (EDA)
- ✅ Preprocessing: lowercasing, punctuation removal, stemming
- ✅ Vectorization using `Tokenizer`
- ✅ Model: Sequential Neural Network with `Dense`, and `ReLU` activations
- ✅ Evaluation: Accuracy, and sample prediction outputs
- ✅ Model saving in `.h5` format for later inference

---

## 📦 Dependencies

To run this notebook, make sure you install:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras

## ▶️ How to Run

### 🔁 Clone the Repository

```bash
git clone https://github.com/AtulKharat256/Comment_Toxicity.git
cd Comment_Toxicity

## Run the jupyter notebook
jupyter notebook Comment_Toxicity.ipynb

