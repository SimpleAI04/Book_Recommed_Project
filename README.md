## 📚 Book Recommendation System (Capstone Project)

This is the final project from the **Samsung Innovation Campus**, aimed at building a personalized book recommendation system using **K-Nearest Neighbors (KNN)** and **Autoencoder** techniques.

The goal is to recommend books based on users' preferences and reading history by combining simple and deep learning methods for improved accuracy and efficiency.

### 🔍 Key Highlights

- Explored and visualized user-book interaction data.
- Used KNN (brute-force cosine similarity) for baseline recommendations.
- Employed Autoencoder to reduce feature dimensionality and enhance retrieval quality.
- Focused heavily on **data preprocessing** to ensure high-quality input.

### 🧪 Notebooks

- `original_model.ipynb`: Data analysis & KNN implementation.
- `optimize_model.ipynb`: Autoencoder model for dimensionality reduction.

---

## 🛠 Technologies Used

- Python, Pandas, NumPy
- Scikit-learn, TensorFlow, Keras
- Streamlit (for UI demo)

---

## 🛠️ Implementation

📄 Main Notebooks:
- `original_model.ipynb`: Baseline KNN approach
- `optimize_model.ipynb`: Autoencoder training & optimization

📄 App:
- `app.py`: Script to run local Flask-based demo

📄 Output:
- `recommended_books.txt`: Example output recommendations

---

## ⚙️ Requirements
    pip install -r requirements.txt
## ⚡ Run Demo
    python app.py

## 👨‍💻 My Role

As **Team Member** (in a team of 6), I contributed to:

- 🔧 Project planning & team coordination
- 🧹 Data cleaning & transformation
- 📊 Visualization & exploratory analysis
- 🧩 KNN model development

---

📁 Project Structure
```
Project-Book_Recommed/
│
├── data/                     # Raw data
├── artifacts/                # Preprocessed & model files
├── Final Report/             # PDF + slides for capstone
├── app.py                    # Demo script
├── original_model.ipynb      # KNN model code
├── optimize_model.ipynb      # Autoencoder model code
├── recommended_books.txt     # Example result
├── requirements.txt
└── README.md                 # You're here!
```
