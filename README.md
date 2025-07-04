# 📰 Fake News Detection using Flask & Machine Learning

This is a web application that detects whether a given news article is **Real** or **Fake** using Natural Language Processing (NLP) and Machine Learning (Logistic Regression).

![Fake News Detection Demo](https://your-screenshot-or-demo-link.png)

---

## 🚀 Features

- 🌐 Web interface built using Flask, HTML, CSS, and JavaScript
- 🧠 NLP-based text classification using TF-IDF and Logistic Regression
- ✅ Detects both titles and full article text
- 📊 Displays prediction with confidence and reasoning
- 💬 Flash messages and input validation

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas, NumPy
- TF-IDF Vectorizer
- HTML, CSS (Vanilla)
- NLTK (for text cleaning)

---

## 📂 Folder Structure

```

FakeNewsDetection-Flask/
├── app.py
├── requirements.txt
├── README.md
├── model/
│   ├── fake\_news\_model.pkl
│   └── tfidf\_vectorizer.pkl
├── static/
│   └── style.css
├── templates/
│   ├── index.html
│   ├── check.html
│   └── result.html

````

---

## ⚙️ How to Run Locally

1. **Clone this repo:**
   ```bash
   git clone https://github.com/your-username/FakeNewsDetection-Flask.git
   cd FakeNewsDetection-Flask
````

2. **Create virtual environment (optional):**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app:**

   ```bash
   python app.py
   ```

5. **Open in browser:**
   Visit `http://127.0.0.1:5000` in your browser

---

## 📦 Requirements (requirements.txt)

```txt
Flask
scikit-learn
pandas
numpy
nltk
joblib
```

---

## 📸 Screenshots

### 🏠 Home Page

![Home](https://github.com/codedbyasim/FakeNewsDetection-Flask/blob/main/Home.PNG)

### 📝 Check Page

![Check](https://github.com/codedbyasim/FakeNewsDetection-Flask/blob/main/Check.PNG)

### 📊 Result Page

![Result](https://github.com/codedbyasim/FakeNewsDetection-Flask/blob/main/Result.PNG)

---

## 👨‍💻 Author

**Asim Hanif**
Software Engineering Student
🔗 [LinkedIn](https://www.linkedin.com/in/codedbyasim)
📧 [Gmail](mailto:asimjutt2003@gmail.com)

---

## 📄 License

MIT License – Use freely and modify 😊
