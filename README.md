 # Fake News Prediction

This project predicts whether a given news article is **real** or **fake** using Natural Language Processing (NLP) and machine learning techniques.  
It is implemented in Python using a Jupyter Notebook.

## 📌 Features
- Data loading and preprocessing (text cleaning, tokenization, stopword removal).
- Feature extraction using TF-IDF Vectorization.
- Machine learning model training and evaluation.
- Prediction for custom news text input.

## 🛠️ Technologies Used
- Python 3.x
- NumPy & Pandas (data handling)
- Scikit-learn (ML algorithms & metrics)
- NLTK (natural language processing)
- Jupyter Notebook

## 📂 Project Structure
```
Fake_News_Prediction.ipynb  # Main notebook
requirements.txt            # Python dependencies
README.md                   # Project documentation
```

## 🚀 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/your-username/fake-news-prediction.git
cd fake-news-prediction
```

2. **Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate     # For Linux/Mac
venv\Scripts\activate      # For Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run Jupyter Notebook**
```bash
jupyter notebook Fake_News_Prediction.ipynb
```

## 📊 Dataset
The dataset contains labeled news articles with:
- `title` – the headline of the news article
- `text` – the body of the news article
- `label` – 1 for fake news, 0 for real news

## 📈 Model Training
- Preprocess text data (lowercasing, punctuation removal, stopword removal).
- Convert text into numerical features using **TF-IDF Vectorization**.
- Train ML model (e.g., Logistic Regression).
- Evaluate performance using accuracy score, confusion matrix, and classification report.
