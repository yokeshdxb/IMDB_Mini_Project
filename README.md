# 🎬 IMDB Ratings Prediction using Machine Learning

This mini-project involves performing exploratory data analysis and building regression models to predict IMDB ratings of movies based on multiple features such as genre, duration, number of votes, and release year.

---

## 📌 Project Highlights

- 🔄 Cleaned and transformed raw IMDB data (handled nulls, cleaned vote counts, parsed duration)
- 🔍 Conducted Exploratory Data Analysis (EDA) using seaborn and matplotlib
- 🔢 Performed Feature Engineering:
  - One-hot encoding of genres and year ranges
  - Numeric transformation of duration and vote counts
- 🧠 Built and evaluated three machine learning models:
  - **Linear Regression**
  - **Random Forest Regressor**
  - **Gradient Boosting Regressor**
- 🎯 Tuned hyperparameters using **GridSearchCV**
- 📊 Extracted and visualized **feature importances** from the best-performing model

---

## 🧪 Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – data manipulation
  - `seaborn`, `matplotlib` – visualization
  - `scikit-learn` – model training, evaluation, and tuning

---

## 📂 Dataset

- File: `shows.csv`
- Columns include:
  - `title`, `genre`, `imbd_rating`, `imbd_votes`, `duration`, `certificate`, `year`, `rank`, etc.

---

## 📈 Evaluation Metrics

Each model is evaluated using:
- **MSE** (Mean Squared Error)
- **RMSE** (Root Mean Squared Error)
- **R² Score**

---

## 📊 Results

- Gradient Boosting Regressor gave the best performance after hyperparameter tuning.
- Key predictive features: `imbd_votes`, `rank`, certain genres, and release decade.
- Visualized residuals and feature importance to interpret model behavior.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/imdb-rating-prediction.git
   cd imdb-rating-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook or Python script:

Open IMDB_Rating_Prediction.ipynb in Jupyter Notebook

Or run python imdb_rating_model.py

👏 Acknowledgements
Grateful to my mentors Raja, Pranav, Chirag, and Sandhya for their guidance throughout this project.

📎 License
This project is open-source and available under the MIT License.

🌐 Connect
Feel free to connect with me on LinkedIn or check out more of my work on GitHub.
