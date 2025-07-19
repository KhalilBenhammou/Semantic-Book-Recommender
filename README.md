# Semantic Book Recommender 📚✨

A semantic book recommendation engine powered by Hugging Face embeddings, LangChain, and Gradio.

---

## 📖 Project Overview

The Semantic Book Recommender allows users to find books based on natural language queries, selected categories, and emotional tones. Leveraging semantic embeddings, it matches user queries with book descriptions to recommend relevant and emotionally aligned books.

Initial dataset source: [7k Books with Metadata (Kaggle)](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata)

---

## 🚀 Features

- **Semantic Search** leveraging Hugging Face embeddings (`sentence-transformers/all-MiniLM-L6-v2`)
- **Category-based Filtering**
- **Emotion-based Sorting** across seven distinct emotions (Joy, Surprise, Anger, Fear, Sadness, Disgust, Neutral)
- **Interactive Dashboard** built with Gradio for intuitive user interaction

---

## 📁 Project Structure

```
semantic-book-recommender/
│
├── data/
│   ├── books_cleaned.csv
│   ├── books_with_categories.csv
│   ├── books_with_emotions.csv
│   └── tagged_description.txt
│
├── notebooks/
│   ├── data-exploration.ipynb
│   ├── sentiment-analysis.ipynb
│   ├── text-classification.ipynb
│   └── vector-search.ipynb
│
├── src/
│   └── gradio-dashboard.py
│
├── README.md
└── requirements.txt
```
---

## 🗃️ Datasets

The project uses datasets derived from the 7k Books with Metadata Kaggle dataset:

- `books_cleaned.csv`: Cleaned dataset containing essential book metadata.
- `books_with_categories.csv`: Books enriched with categorized information.
- `books_with_emotions.csv`: Annotated dataset with emotional tones (Joy, Surprise, Anger, Fear, Sadness, Disgust, Neutral).
- `tagged_description.txt`: Book descriptions tagged with ISBN identifiers, enabling semantic search.

---

## 📓 Notebooks Overview

Explore the analysis and development process through interactive notebooks:

- **Data Exploration**: Initial data analysis and insights.
- **Sentiment Analysis**: Emotional tone analysis of book descriptions.
- **Text Classification**: Automated categorization based on description text.
- **Vector Search**: Implementation of semantic vector-based searching.

---

## 📦 Dependencies

- Pandas
- Seaborn 
- NumPy
- Kagglehub
- Notebook
- Gradio  
- LangChain  
- Hugging Face Embeddings (`sentence-transformers/all-MiniLM-L6-v2`)  
- ChromaDB  

---

Happy Reading! 📖✨
