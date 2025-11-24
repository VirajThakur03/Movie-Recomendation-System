# Movie-Recomendation-System

# 🎬 Simple Movie Recommender App  
A **Content-Based Movie Recommendation System** built using **Python, Streamlit, Pandas, and Scikit-Learn**.

## 🚀 Features  
- Select a movie from a dropdown list  
- Get top 10 similar movies  
- Fast content-based filtering  
- Clean Streamlit UI  
- Pre-trained TF-IDF & similarity matrix  

## 📁 Project Structure  
```
📦 Movie-Recommender
│
├── app.py
├── movie_data_for_app.csv
├── movie_dataframe_for_app.csv
├── sigmoid_kernel.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
└── README.md
```

## 🔧 Installation  
```bash
git clone https://github.com/YourUsername/YourRepoName.git
cd YourRepoName
python -m venv myenv
myenv\Scripts\activate    # Windows
pip install -r requirements.txt
```

## ▶️ Run the App  
```bash
streamlit run app.py
```

## 🧠 How It Works  
1. TF-IDF Vectorization  
2. Sigmoid Kernel Similarity  
3. Precomputed similarity matrix  
4. Content-Based Filtering  

## 📦 Requirements  
```
streamlit
pandas
joblib
scikit-learn
```



