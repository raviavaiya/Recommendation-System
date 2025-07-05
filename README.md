# 🍽️ Food & Product Recommender System

🚀 Excited to Start a New Project!
I'm building an intelligent Recommendation System that enhances user experience by suggesting the right food products or other items, just like Amazon does! Whether you're shopping for groceries, meals, or essentials — this system aims to deliver personalized suggestions that matter. 🍱🛒✨
<img align="right" alt="Recommender System" width="600" src="https://github.com/raviavaiya/Recommendation-System/blob/main/static/Food-Recommendation-System.png">

## 🔍 Project Goals

- Understand user preferences and behavior to make intelligent product recommendations.

- Enhance user satisfaction and engagement in the food/product browsing journey.

- Explore real-world applications of AI and machine learning in e-commerce and food tech.


## 🚀 Features

### 🔍 Filter food items based on:

- Protein, Fat, and Carbohydrate levels (in grams)

- Food type preference (Veg / Non-Veg)

### 🤖 Recommend products using:

- Collaborative Filtering

- Content-Based Filtering

## 🧠 Track user behavior for personalized insights

### ⚙️ Real-time API-based recommendations

## 🛠️ Technologies & Concepts

- Machine Learning – Collaborative & Content-Based Filtering

- Python – pandas, NumPy, scikit-learn

- FastAPI – Backend REST API

- HTML/CSS – Frontend user interface

- MySQL – Food & user data storage

- Streamlit / Flask (Planned) – For interactive web interfaces

- User Analytics – For behavior tracking & smart personalization



## 📦 Project Structure

food-recommender/
├── backend/
│   └── main.py             # FastAPI backend logic
├── frontend/
│   ├── index.html          # UI to display recommendations
│   └── style.css           # Optional styling
├── data/
│   └── food_data.sql       # SQL dump of food nutrition data
├── README.md


## 🧪 Sample Food Dataset

| Food_Name | F_type  | Ingredients       | Protein (g) | Fat (g) | Carbos (g) |
|-----------|---------|-------------------|-------------|---------|------------|
| Apple     | Fruit   | Apple             | 0.3         | 0.2     | 14         |
| Chicken   | Meat    | Chicken breast    | 31          | 3.6     | 0          |
| Rice      | Grain   | White rice        | 2.7         | 0.3     | 28         |
| Paneer    | Veg     | Cottage cheese    | 18          | 20      | 1.2        |
| Eggs      | Non-Veg | Eggs              | 13          | 11      | 1.1        |

## 🔧 How to Run Locally

### 1. Clone the Repository

git clone https://github.com/raviavaiya/food-recommendation_system.git
cd food-recommendation_system

### 2. Setup MySQL
Create a database and import food_data.sql located in data/ folder.

### 3. Setup and Run FastAPI Backend

cd backend
pip install fastapi uvicorn pymysql
uvicorn main:app --reload

### 4. Open Frontend
Open frontend/index.html in your browser to interact with the recommender system.

## 📈 Future Enhancements

- 🖼️ Add image-based recommendations (CDN/browser preview)

- 🔐 Add login/authentication system

- ⭐ Capture user feedback and ratings

- 🤖 Integrate ML models for smarter product suggestions

- 🌐 Build a Streamlit/Flask-powered UI for deployment


## 🙌 Contributing
Feel free to fork this repo and suggest improvements via pull requests!

## 💬 Let’s Connect!

If you’ve worked on something similar or have ideas to share, I’d love to connect and learn from your experience!

Made with ❤️ for curious shoppers and foodies.
