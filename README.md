# 📚 Book Recommendation System – AI Project
This project is a basic AI-powered book recommendation system built using collaborative filtering. It suggests books similar to a title provided by the user, based on patterns in user rating data.

---
## 💡 How It Works:
- Uses a dataset of books, users, and user ratings  
- Builds a user-item matrix from ratings  
- Computes similarity between books using cosine similarity  
- Returns top 5 similar books for any given title  

---
## 🔧 Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Google Colab  
---
## 📁 Dataset
The dataset includes:
- `Books.csv` — Book metadata (title, author, etc.)  
- `Ratings.csv` — User ratings for books  
- `Users.csv` — User info (not used in this model)  
---
## 🚀 How to Use
1. Open `book.ipynb` in Google Colab  
2. Upload the dataset ZIP file when prompted  
3. Run all cells  
4. Enter a book title (e.g. `"The Da Vinci Code"`) when asked  
5. Get 5 recommended books based on rating similarity  

---
## 🔍 Example Prompts

Try book titles like:

- The Da Vinci Code  
- The Lovely Bones: A Novel  
- The Red Tent (Bestselling Backlist)  
- Wild Animus  
- A Time to Kill  
---

