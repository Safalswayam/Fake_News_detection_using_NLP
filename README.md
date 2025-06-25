📰 Fake News Detection using NLP
This project applies Natural Language Processing (NLP) and Machine Learning to detect whether a given news article is real or fake. It uses TF-IDF for text vectorization and a PassiveAggressiveClassifier for classification.

🎯 Objective
To build a binary classification model that classifies news content as:

1 → Fake

0 → Real

📂 Dataset
Source: Fake and True News Dataset

File: true.xlsx
      fake.xlsx

Contains text and labels for thousands of news articles.

🔍 Features
text: The news article content

label: Target variable (FAKE or REAL)

The label is converted to binary (1 for fake, 0 for real).

🧠 Model & Techniques
TF-IDF Vectorizer: Converts text into numerical features

PassiveAggressiveClassifier: A fast linear classifier suitable for large-scale and online learning

🛠️ Tools Used
Python

Pandas

Scikit-learn

TF-IDF (TfidfVectorizer)

Jupyter Notebook

⚙️ Workflow
Load and clean the dataset

Convert labels to binary format

Vectorize the text using TF-IDF

Split the dataset into training and test sets

Train the PassiveAggressiveClassifier

Evaluate using accuracy, confusion matrix, and classification report

📊 Evaluation Metrics
Accuracy

Precision / Recall / F1-Score

Confusion Matrix

🧪 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Safalswayam/fake-news-detection.git
cd fake-news-detection
Place news.csv in the root folder

Open Fake_News_Detection.ipynb in Jupyter Notebook

Run all cells sequentially
