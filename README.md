# Sentiment Analysis Web Application

A simple web application built with **Flask** and **Python** that uses Natural Language Processing (NLP) to analyze the sentiment of user-provided text.

## 🚀 Features

- Analyze the sentiment of any text (Positive, Negative, Neutral, or Mixed).
- Clean and interactive user interface with responsive design.
- Visual representation of sentiment results.
- Real-time analysis using libraries like **NLTK**, **VADER**, and **sklearn**.

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS (for styling)
- **Backend:** Flask (Python framework)
- **Libraries:** NLTK, VADER, scikit-learn

## 📂 Project Structure
```
├── static
│   └── style.css          # CSS for styling the web app
├── templates
│   ├── form.html          # Main HTML page with the input form
├── app.py                 # Flask server and logic for sentiment analysis
├── requirements.txt       # List of Python dependencies
└── README.md              # Project documentation (this file)
```

## 🔧 Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/sentiment-analysis-flask.git
cd sentiment-analysis-flask
```

2. **Create a virtual environment:**
```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Run the Flask app:**
```bash
set FLASK_APP=app.py       # On Windows (PowerShell)
export FLASK_APP=app.py    # On macOS/Linux

flask run
```

The app will run on: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## 🧠 How Sentiment Analysis Works

The app uses:
- **TF-IDF Vectorizer** for text feature extraction.
- **VADER (Valence Aware Dictionary and sEntiment Reasoner)** for sentiment scoring.
- **Cosine Similarity** (optional) for measuring the similarity between sentences.

## 🚀 Usage
1. Enter a paragraph or sentence in the text box.
2. Click the **Analyze** button.
3. View the sentiment result with the corresponding label and confidence score.

## 🛡️ License
This project is licensed under the MIT License. Feel free to modify and use it for your projects!


✨ *Happy Coding!* ✨

---
Let me know if you want me to add anything or tweak the structure! 🚀

