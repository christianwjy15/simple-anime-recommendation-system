# Anime Recommendation System

This project is a **content-based recommendation system** that suggests similar anime based on their **synopsis**. It uses **TF-IDF vectorization** and **cosine similarity** to determine relevance between anime descriptions.
Use dataset from [Kaggle Anime Recommendation Database 2020](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020)


## How It Works

1. **Text Vectorization**: Each anime synopsis is converted into numerical form using **TF-IDF (Term Frequency–Inverse Document Frequency)**.
2. **Similarity Calculation**: Using **cosine similarity**, the system compares how close each synopsis is to others.
3. **Recommendation**: Given a selected anime, the system returns a list of similar anime titles based on the synopsis content.

## Technologies Used

- Python
- pandas
- scikit-learn (`TfidfVectorizer`, `cosine_similarity`)
- numpy

