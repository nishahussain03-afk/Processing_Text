# 📝 Text Preprocessing Using NLTK

## 📌 Project Overview

This project demonstrates **Text Preprocessing** in **Natural Language Processing (NLP)** using **Python**, **NLTK**, **Regular Expressions (Regex)**, and **Pandas**.

The notebook reads raw text from a text file, performs preprocessing techniques such as text cleaning, tokenization, stopword removal, and lemmatization, and saves the processed text into output files.

---

## 🎯 Objectives

- Read raw text from a text file
- Convert text to lowercase
- Remove URLs
- Remove email addresses
- Remove phone numbers
- Remove HTML tags
- Remove hashtags and mentions
- Remove emojis
- Remove punctuation
- Remove numbers
- Remove extra spaces
- Tokenize the text
- Remove stopwords
- Perform lemmatization
- Save cleaned text into output files

---

## 🛠 Technologies Used

- Python
- Google Colab
- NLTK
- Pandas
- Regular Expressions (Regex)

---

## 📂 Project Structure

```text
Text-Preprocessing-Using-NLTK/
│
├── Preprocessing_Text.ipynb
├── raw_data.txt
├── output.txt
├── clean.csv
├── README.md
└── requirements.txt
```

---

## 📚 Python Libraries

- pandas
- nltk
- re
- string

---

## ⚙️ Preprocessing Steps

1. Import the required libraries.
2. Download NLTK resources.
3. Upload the input file (`raw_data.txt`).
4. Read the text file.
5. Convert text to lowercase.
6. Remove URLs.
7. Remove email addresses.
8. Remove phone numbers.
9. Remove HTML tags.
10. Remove hashtags and mentions.
11. Remove emojis.
12. Remove punctuation.
13. Remove numbers.
14. Remove extra spaces.
15. Tokenize the text.
16. Remove stopwords.
17. Perform lemmatization.
18. Save the cleaned text as `output.txt`.
19. Save the cleaned words as `clean.csv`.

---

## 📥 Input

**Input File:** `raw_data.txt`

Example:

```text
Hello Everyone!!

Welcome to NLP Text Preprocessing.

Visit https://www.example.com

Email: support@example.com

Phone: +91-9876543210

<div>This is HTML Content</div>

#ArtificialIntelligence @OpenAI 😊

Natural Language Processing (NLP) is one of the most exciting fields in Artificial Intelligence.

Python, NLTK, and Pandas are widely used for text preprocessing.
```

---

## 📤 Output

The notebook generates two output files:

- **output.txt** – Contains the cleaned text.
- **clean.csv** – Contains the cleaned words in CSV format.

---

## 💻 How to Run in Google Colab

### Step 1

Open **Google Colab**.

https://colab.research.google.com

### Step 2

Upload **Preprocessing_Text.ipynb**.

### Step 3

Install the required libraries and download NLTK resources.

```python
!pip install nltk pandas

import nltk

nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
```

### Step 4

Upload the input file.

```python
from google.colab import files

uploaded = files.upload()
```

Select **raw_data.txt**.

### Step 5

Run all notebook cells.

### Step 6

The notebook automatically creates:

- `output.txt`
- `clean.csv`

### Step 7

Download the generated files.

```python
from google.colab import files

files.download("output.txt")
files.download("clean.csv")
```

---

## 📊 Applications

- Natural Language Processing (NLP)
- Sentiment Analysis
- Text Classification
- Chatbots
- Spam Detection
- Machine Learning
- Information Retrieval

---

## 🚀 Future Enhancements

- Stemming
- Part-of-Speech (POS) Tagging
- Named Entity Recognition (NER)
- TF-IDF Vectorization
- Text Summarization

---

## 📸 Sample Output

### output.txt

```text
hello everyone welcome nlp text preprocessing visit detail contact html content natural language processing one exciting field artificial intelligence python nltk pandas widely used text preprocessing
```

### clean.csv

| Cleaned_Text |
|---------------|
| hello |
| everyone |
| welcome |
| nlp |
| text |
| preprocessing |
| visit |
| detail |
| contact |
| html |
| content |
| natural |
| language |
| processing |
| artificial |
| intelligence |
| python |
| nltk |
| pandas |

---

## 👨‍💻 Author

**Your Name**

B.Sc. Computer Science with Artificial Intelligence

---

⭐ If you found this project useful, consider giving it a **Star ⭐** on GitHub.
