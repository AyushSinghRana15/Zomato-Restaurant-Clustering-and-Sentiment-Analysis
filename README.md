# 🍽️ Zomato-Restaurant-Clustering-and-Sentiment-Analysis

This project performs unsupervised **clustering of restaurants** and supervised **sentiment analysis** of reviews from the Zomato dataset to derive actionable business insights. It utilizes popular machine learning techniques such as **K-Means**, **DBSCAN**, **LDA (Topic Modeling)**, and **Logistic Regression/XGBoost** for text classification.


---

## 🧠 Key Features

- 📊 **Clustering Analysis (K-Means, DBSCAN)** based on cost, rating, and cuisine count
- 🗂️ **Topic Modeling** using LDA to extract dominant review themes
- 💬 **Sentiment Classification** using Logistic Regression and XGBoost
- 📈 **Evaluation Metrics:** Silhouette Score, F1-Score, Precision, Recall, ROC AUC
- 📌 **Business Insights** derived from cluster-wise cuisine and sentiment trends

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- NLTK / spaCy
- XGBoost
- Gensim (for LDA Topic Modeling)

---

## 🚀 How to Run This Project

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/AyushSinghRana15/Zomato-Restaurant-Clustering-and-Sentiment-Analysis.git
cd Zomato-Restaurant-Clustering-and-Sentiment-Analysis
```
2: Open Anaconda Navigator\
Launch Anaconda Navigator from your Start Menu (Windows) or Applications folder (Mac).\
Click on Environments (left sidebar).\
Click Create:
Name: zomato_env
Python version: 3.9 (or 3.8+)\
Wait for environment creation to complete.\
Step 3: Install Required Libraries
Select your new environment (zomato_env) from the Environments tab.\
From the dropdown, choose "Not installed".\
Use the search bar to find and check these packages:
pandas\
numpy\
matplotlib\
seaborn\
scikit-learn\
nltk\
gensim\
xgboost\
Click Apply to install selected packages.\
For any missing packages (e.g., xgboost or gensim), you can also open a terminal inside Navigator (click "▶" > Open Terminal) and run:\
pip install xgboost gensim nltk spacy\
Then, install NLTK resources:

import nltk
nltk.download('punkt')\
nltk.download('stopwords')\

4. Launch Jupyter Notebook\
Go to Home tab in Anaconda Navigator.\
In the Applications on zomato_env section:
Locate Jupyter Notebook
Click Launch\
A browser window will open.\
Step 5: Open the Project\
In the browser window, navigate to the folder where you cloned/downloaded the project.\
Open:
Zomato-Restaurant-Clustering-and-Sentiment-Analysis.ipynb\
Run each cell in sequence to execute the notebook.\
Optional: Add zomato_env to Jupyter Kernels\
If Jupyter doesn't show your new environment:

Open terminal inside Anaconda Navigator (▶ > Terminal in zomato_env)
Run:
python -m ipykernel install --user --name=zomato_env
Now you'll see zomato_env as a kernel inside Jupyter Notebook.\

✅ Project Features:

📊 Restaurant Clustering using KMeans, DBSCAN, and PCA\
💬 Sentiment Analysis using NLP, LDA topic modeling\
🎯 Model Evaluation with Precision, Recall, F1-Score, ROC AUC\
🧠 Supervised Learning with Logistic Regression, XGBoost\
📈 Visual analytics using matplotlib and seaborn




