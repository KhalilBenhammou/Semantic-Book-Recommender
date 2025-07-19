# Semantic Book Recommender 📚✨

A semantic book recommendation engine powered by Hugging Face embeddings, LangChain, and Gradio.

## 📖 Project Overview

The Semantic Book Recommender allows users to find books based on a natural language query, selected categories, and emotional tones. It utilizes semantic embeddings to match user queries with book descriptions and recommends the most relevant and emotionally aligned books.

## 🚀 Features

- **Semantic Search** using Hugging Face Embeddings (`sentence-transformers/all-MiniLM-L6-v2`).
- **Category-based Filtering**.
- **Emotion-based Sorting** (Joy, Surprise, Anger, Fear, Sadness, Disgust, Neutral).
- **Interactive User Interface** built with Gradio.

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

## ⚙️ Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/your_username/semantic-book-recommender.git
cd semantic-book-recommender
```

### Step 2: Set up a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Step 3: Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Running the Dashboard

Start the Gradio dashboard by running:

```bash
python src/gradio-dashboard.py
```

Open your web browser and navigate to the URL provided in the terminal to interact with the recommender.

## 🗃️ Datasets

The following datasets are included:

- **books\_cleaned.csv**: Cleaned dataset containing basic book details.
- **books\_with\_categories.csv**: Dataset with additional categorization information.
- **books\_with\_emotions.csv**: Dataset annotated with emotional tones (joy, surprise, anger, fear, sadness).
- **tagged\_description.txt**: Text file containing book descriptions tagged with ISBN identifiers for semantic search.

## 📓 Notebooks Overview

Explore the development stages through interactive Jupyter Notebooks:

- [**Data Exploration**](notebooks/data-exploration.ipynb): Initial exploration and analysis of datasets.
- [**Sentiment Analysis**](notebooks/sentiment-analysis.ipynb): Sentiment and emotion analysis of book descriptions.
- [**Text Classification**](notebooks/text-classification.ipynb): Categorizing books based on descriptions.
- [**Vector Search**](notebooks/vector-search.ipynb): Implementing semantic search using embeddings.

## 📦 Dependencies

- Pandas
- NumPy
- Gradio
- LangChain
- HuggingFace Embeddings (`sentence-transformers`)
- ChromaDB

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

## 📜 License

This project is licensed under the MIT License.

## 📧 Contact

- **GitHub**: [Your GitHub Profile](https://github.com/your_username)
- **Email**: [your.email@example.com](mailto\:your.email@example.com)

---

**Happy Reading!** 📖✨

