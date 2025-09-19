
# 🎬 CineScore AI: Intelligent IMDb Rating Predictor 🎥  

 ## Project Overview  
CineScore AI is a **machine learning-based IMDb score prediction system** that analyzes **movie metadata, genres, ratings, and audience engagement metrics** to predict IMDb scores accurately. The project also explores insights into **what makes a movie successful**, helping **streaming platforms, production studios, and movie enthusiasts** make data-driven decisions.  

##  Features  
-  **Data Cleaning & Preprocessing** (Missing values, outlier treatment, feature scaling)  
-  **Feature Engineering** (TF-IDF Vectorization, Categorical Encoding, New Feature Creation)  
-  **Exploratory Data Analysis (EDA)** (15+ insightful visualizations)  
-  **Dimensionality Reduction** (Truncated SVD for high-dimensional TF-IDF data)  
-  **Handling Imbalanced Data** (SMOTE oversampling for fairer model training)  
-  **Machine Learning Model** (Gradient Boosting Regressor for IMDb score prediction)  
-  **Model Evaluation** (Mean Squared Error, R² Score)  

##  Dataset  
The dataset includes **movie and TV show details from Amazon Prime**, consisting of:  
- **IMDb scores, TMDB popularity, votes**  
- **Movie descriptions, genres, age certifications**  
- **Production details (countries, release years, runtimes, etc.)**  

##  Folder Structure  

```bash
├── data/                  # Raw and processed datasets  
├── notebooks/             # Jupyter notebooks for EDA & ML modeling  
├── src/                   # Python scripts for preprocessing & modeling  
├── models/                # Saved trained models  
├── images/                # Visualization charts  
├── README.md              # Project documentation  
└── requirements.txt       # Dependencies list  
````

## 🛠️ Tech Stack

*  **Python (Pandas, NumPy, Scikit-Learn, NLTK, Seaborn, Matplotlib, imbalanced-learn)**
*  **Machine Learning Models: Gradient Boosting, Random Forest**
*  **Text Processing: TF-IDF Vectorization, POS Tagging, Feature Engineering**
*  **Dimensionality Reduction: Truncated SVD**
*  **Data Handling: Label Encoding, Feature Scaling, Missing Value Imputation**

## 📈 Key Insights from EDA

*  **High-rated movies tend to have more votes, confirming audience engagement matters.**
*  **Genres like Drama & Sci-Fi receive higher IMDb scores, while Horror has mixed ratings.**
*  **Older movies (pre-2000) generally have higher IMDb scores compared to recent films.**
*  **Movies with a runtime between 90-120 minutes tend to perform better.**
*  **IMDb & TMDB scores are positively correlated, but platform biases exist.**

##  Model Performance

✔ **Mean Squared Error (MSE):** *\[Add value]*
✔ **Mean Absolute Error (MAE):** *\[Add value]*
✔ **R-Squared Score (R²):** *\[Add value]*

##  Future Improvements

*  Use **Deep Learning (LSTMs or Transformers)** for better text-based predictions
*  Expand dataset to include **Netflix, Disney+, Hulu** for a comparative study
*  Improve recommendation system using **Content-Based & Collaborative Filtering**

##  How to Use

1️⃣ **Clone the repository:**

```bash
git clone https://github.com/yourusername/CineScore-AI.git
cd CineScore-AI
```

2️⃣ **Install dependencies:**

```bash
pip install -r requirements.txt
```

3️⃣ **Run the Jupyter notebook:**

```bash
jupyter notebook
```

 **CineScore AI – Bringing Data-Driven Intelligence to Movie Ratings!** 

```
###  What I Fixed:
- Added **spaces after `#`** in all headings.  
- Closed code fences properly.  
- Converted checkmarks into list items under Features for clean alignment.  
- Used **bash syntax highlighting** for directory tree and commands.  


