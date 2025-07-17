# 🎬 Hybrid Movie Recommendation System

A smart movie recommendation engine that combines **Popularity-Based**, **Content-Based**, and **Item-Based Collaborative Filtering** techniques to provide personalized and trending movie suggestions.

This project uses machine learning techniques to recommend movies to users based on overall popularity, movie metadata, and similarity between user preferences.

It is a  hybrid movie recommendation system that intelligently suggests movies to users based on their interests and overall movie popularity.

---

## Recommender Systems Used

**1. Popularity-Based Filtering**  
Recommends globally top-rated or most-watched movies. Ideal for new users without prior interactions.

**2. Content-Based Filtering**  
Recommends similar movies based on metadata such as genres, keywords, cast, director, and description.  
Implemented using **TF-IDF vectorization** and **cosine similarity** to measure text-based feature closeness.

**3. Item-Based Collaborative Filtering**  
Suggests movies similar to those a user has already rated highly, using behavior patterns of all users.  
Built using a **user-movie rating pivot table** and **Pearson correlation** to compute item-to-item similarity.


---

## ⚙️ Technologies Used

- **Python**
- `Pandas` for data manipulation
- `Scikit-learn` for TF-IDF & cosine similarity
- `NumPy` for matrix operations
- `Matplotlib` for visualizations

---

## 🚀 How to Use

1. Clone the repo:  
   `git clone https://github.com/Jai-Anand-JA/MovieRecommender.git`

2. Navigate to the folder:  
   `cd MovieRecommender`

3. Run the html or ipynb files after downloading the required datasets

5. Make sure to upload `movies.csv` and `ratings.csv` when prompted.

---
## Author
- Jai Anand
