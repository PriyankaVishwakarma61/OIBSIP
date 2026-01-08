
# 📧 Email Spam Detection using Machine Learning

Spam emails (junk mails) are unwanted messages sent in bulk that often contain advertisements, scams, or phishing links.  
This project uses **Python and Machine Learning** to build an **Email Spam Detection system** that classifies emails as **Spam** or **Not Spam (Ham)**.

---

## 🎯 Project Objective

- Detect spam emails automatically  
- Apply Natural Language Processing (NLP) techniques  
- Train a Machine Learning model for classification  
- Achieve high accuracy in spam detection  

---

## 🧠 Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- TF-IDF Vectorizer  
- Multinomial Naive Bayes  

---

## 📂 Dataset Information

- **Dataset Name:** `spam.csv`
- **Source:** UCI SMS Spam Collection Dataset
- **Columns:**
  - `v1` → Label (`spam` / `ham`)
  - `v2` → Email/Text message

---

## 🔄 Project Workflow

1. Load the dataset  
2. Clean and preprocess the data  
3. Convert text into numerical form using TF-IDF  
4. Split data into training and testing sets  
5. Train the Naive Bayes classifier  
6. Evaluate the model  
7. Predict new email messages  

---

## 🧪 Machine Learning Model

### Multinomial Naive Bayes
- Best suited for text classification  
- Fast and efficient  
- Widely used for spam detection  

---

## 📈 Model Performance

- **Accuracy:** ~97–99%  
- Evaluation Metrics:
  - Accuracy Score
  - Precision
  - Recall

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/email-spam-detection.git
