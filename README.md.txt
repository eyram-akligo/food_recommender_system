# Hybrid Food Recommender System

This project is my final-year capstone for the BSc. Artificial Intelligence program at Academic City University, Ghana. It is a **hybrid food recommender system** built using collaborative filtering and content-based filtering techniques to suggest top-N recipes to users.

## 🎯 Objective

To develop a recommendation engine that:
- Suggests personalized recipes to users based on their preferences
- Combines collaborative filtering (user-item interaction) with content-based filtering (ingredient similarity, cuisine, etc.)
- Uses the Food.com Recipes and Reviews dataset

## 🧠 Technologies Used

- **Python**
- **Pandas**, **NumPy** for data preprocessing
- **Scikit-learn** for feature engineering
- **Surprise** and **SciPy** for collaborative filtering
- **Matplotlib**, **Seaborn** for visualizations
- **Jupyter Notebook** for prototyping

## 📁 Files

- `hybrid_food_recommender_system.ipynb`: The main Jupyter notebook containing the full pipeline
- `requirements.txt`: Dependencies to run the notebook

## ⚙️ Features

- Collaborative filtering using user-review matrix
- Content-based filtering using TF-IDF on recipe features
- Hybrid ranking algorithm to generate top-N food recommendations
- Evaluation using precision@k and recall@k metrics

📊 Dataset
Food.com Recipes and Reviews

Contains over 500,000 recipes and 1.4 million reviews

Available on Kaggle https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews

🔮 Future Work
Integrate a web-based interface (e.g., with Streamlit or Flask)

Include nutrition-based recommendations

Enable user profile registration and feedback loop

🙌 Acknowledgements
Academic City University, Ghana (Final Year Project)


## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/hybrid-food-recommender-system.git

# Navigate into the directory
cd hybrid-food-recommender-system

# (Optional) Create a virtual environment
python -m venv env
source env/bin/activate   # For Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook
