# MOVIE RECOMMEDATION-SYSTEM
A content-based Movie Recommendation System built using Python in a Jupyter Notebook. This project recommends movies based on user preferences by analyzing features like genres, keywords, cast, and crew from a movie dataset.

## 📌 Features

- Content-based filtering using movie metadata
- Recommends similar movies based on input title
- Utilizes cosine similarity for recommendation ranking
- Built entirely in Jupyter Notebook for ease of exploration and visualization

## 🧠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- NLTK (optional, for advanced preprocessing)
- Matplotlib / Seaborn (for visualization, if used)


- Movie titles
- Links
- Ratings
- Tags

## ⚙️ How It Works

1. Load and preprocess the dataset
2. Combine important features (genre, keywords, cast, crew) into a single string
3. Use `CountVectorizer` to convert text to vectors
4. Apply `cosine_similarity` to find similar movies
5. Return top recommendations for a given movie title

## 🚀 Getting Started

1. Clone the repository or download the notebook file
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn
