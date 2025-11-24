# Movie-Recomendation-System

🎬 Simple Movie Recommender App

A Content-Based Movie Recommendation System built using Python, Streamlit, Pandas, and Scikit-Learn.
This app suggests movies similar to a selected movie based on TF-IDF features and Cosine Similarity (sigmoid kernel).

🚀 Features

✔ Select a movie from a dropdown list
✔ Get the top 10 similar movie recommendations
✔ Fast content-based filtering
✔ Simple and clean Streamlit UI
✔ Uses pre-trained TF-IDF Vectorizer & similarity matrix

📁 Project Structure
📦 Movie-Recommender
│
├── app.py                     # Main Streamlit app
├── movie_data_for_app.csv     # Movie metadata
├── movie_dataframe_for_app.csv
├── sigmoid_kernel.pkl         # Precomputed similarity matrix
├── tfidf_vectorizer.pkl       # Trained TF-IDF Vectorizer
├── requirements.txt           # Dependencies
└── README.md                  # Documentation

🔧 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/YourUsername/YourRepoName.git
cd YourRepoName

2️⃣ Create virtual environment
python -m venv myenv

3️⃣ Activate virtual environment
Windows:
myenv\Scripts\activate

Mac/Linux:
source myenv/bin/activate

4️⃣ Install dependencies
pip install -r requirements.txt

▶️ Run the App

Inside the project folder, run:

streamlit run app.py


Then open the generated URL (usually http://localhost:8501/
) in your browser.

🧠 How It Works
1. TF-IDF Vectorization

Movie descriptions are converted into TF-IDF vectors.

2. Sigmoid Kernel Similarity

Uses sigmoid_kernel to compute similarity between movies.

3. Precomputed Similarity Matrix

To make recommendations faster, the similarity matrix is saved as:

sigmoid_kernel.pkl

tfidf_vectorizer.pkl

4. Content-Based Filtering

Recommends movies with the highest similarity score to user’s selected movie.

📦 Requirements

Create a requirements.txt with:

streamlit
pandas
joblib
scikit-learn
