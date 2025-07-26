# 📧 Spam vs Ham Email Classification using Machine Learning

This project builds a machine learning model to classify emails as spam or ham (legitimate) using Natural Language Processing (NLP) and Logistic Regression.

---

## 🔍 Problem Statement

Email spam detection is an essential task for filtering unwanted emails and improving user experience. This project aims to classify email messages into two categories:

* **Ham (Not Spam)** (label = 1)

* **Spam** (label = 0)

---

## 📁 Dataset

**Source:** *Kaggle SMS Spam Collection Dataset*

**File Used:** *mail_data.csv*

**Features:**

* **Category:** Spam or Ham

* **Message:** Email text

---

## 🛠️ Technologies Used

* **Python (Google Colab)**

* **Libraries: NumPy, Pandas, scikit-learn**

* **Vectorization: TF-IDF** (Term Frequency-Inverse Document Frequency)

* **Modeling: Logistic Regression**

---

## ⚙️ Data Preprocessing

**Null Value Handling:** Replaced null entries with empty strings

**Label Encoding:** Converted spam → 0 and ham → 1

**Feature Extraction:**

* Used **TfidfVectorizer** to transform email text into numerical feature vectors

* **Data Splitting:** Train-Test split *(80% training, 20% testing)*

---

## 🤖 Model Details

* Algorithm: **Logistic Regression**

* Input: **TF-IDF features** from email text

* Evaluation Metric: **Accuracy Score**

---

## 📊 Results

* Training Accuracy: **~96.8%**

* Test Accuracy: **~95.0%**

---

## 🧪 Usage

* Upload *mail_data.csv* to your Colab environment

* Run the notebook cells sequentially

* Enter a custom email message in the predictive system to check if it is spam or ham

---

## 🔮 Future Improvements

* Experiment with advanced models **(SVM, Naive Bayes, or XGBoost)**

* Use **deep learning models (LSTM or Transformers)** for better accuracy

* Add email metadata (sender, subject, etc.) as additional features
