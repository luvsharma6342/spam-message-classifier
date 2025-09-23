# 📱 SMS Spam Classifier (Streamlit + Scikit-learn)

A simple machine learning web app built with **Streamlit** that classifies SMS messages as **Spam** or **Not Spam** using **Multinomial Naive Bayes**.

---

## 🚀 Live Demo
👉 [Try the app on Render]([https://your-render-link-here](https://spam-message-classifier-1-q3qu.onrender.com/))

---

## ⚙️ Features
- Clean UI built with **Streamlit**
- Uses **NLTK** for text preprocessing (tokenization, stopword removal, etc.)
- Trained with **Multinomial Naive Bayes**
- Deployable on **Render**

---

## 🛠️ Installation (Run Locally)

1. Clone this repository:
   ```bash
   git clone https://github.com/luvsharma6342/spam-message-classifier.git
   cd spam-message-classifier
   
2. Create a virtual environment & activate it:
   ```
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows
4. Install dependencies:
   pip install -r requirements.txt

5. Download required NLTK data:
   ```
   import nltk
   nltk.download("punkt")
   nltk.download("punkt_tab")

7. Run the app:
   streamlit run app.py

## 🧠 Model Details

- Algorithm: Multinomial Naive Bayes
- Vectorizer: CountVectorizer / TF-IDF
- Dataset: SMS Spam Collection Dataset (UCI)
## 👨‍💻 Author
- ### Made with ❤️ by Your Name
