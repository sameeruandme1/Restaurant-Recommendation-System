
# 🍽️ Restaurant Recommendation System

This project builds a restaurant recommendation system using PySpark and data analysis techniques. The system provides personalized restaurant suggestions based on user preferences such as location, cuisines, ratings, and more.

## 📘 Project Overview

The goal of this project is to:
- Clean and preprocess restaurant data
- Perform exploratory data analysis (EDA)
- Build content-based and collaborative filtering models
- Recommend restaurants based on user preferences and behaviors

The project is implemented in a Jupyter Notebook: [`Recommendation_System.ipynb`](Recommendation_System.ipynb)

## 📊 Features

- Data cleaning and preprocessing
- Feature engineering for restaurant metadata
- Content-based filtering using cosine similarity
- Collaborative filtering using matrix factorization (e.g., SVD)
- Evaluation metrics (precision, recall, RMSE)
- Visualizations for insights

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Surprise (for collaborative filtering)
- Jupyter Notebook

## 🚀 Getting Started

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/restaurant-recommendation-system.git
cd restaurant-recommendation-system
```

### 2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies:
```bash
pip install -r requirements.txt
```

### 4. Launch the Jupyter Notebook:
```bash
jupyter notebook Recommendation_System.ipynb
```

## 📁 Dataset

This project uses a restaurant dataset with fields such as:
- Restaurant name
- Location
- Online ordering availability
- Table booking availability
- Rating
- Cuisines
- Cost for two
- Type (e.g., café, casual dining)

> **Note:** The dataset is assumed to be preloaded in the notebook. You can replace it with your own restaurant data.

## 📈 Evaluation

The system is evaluated using:
- RMSE for collaborative filtering models
- Cosine similarity match scores for content-based recommendations
- Manual testing for relevance

## 💡 Future Improvements

- Deploy as a web application using Streamlit or Flask
- Integrate user login and profile management
- Include NLP-based cuisine and review analysis

## 📦 requirements.txt

```
pandas
numpy
scikit-learn
matplotlib
seaborn
scipy
notebook
scikit-surprise
```
