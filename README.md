# 🎬 Movie Rating Prediction

This project offers a **machine learning pipeline to predict movie ratings** based on key properties found in a comprehensive movie dataset. :popcorn:

## 📝 Overview

The primary objective is to estimate a movie's rating using attributes such as:

- 🎬 Name  
- 📆 Year of release  
- ⏱️ Duration  
- 🎭 Genre  
- 🎬 Director  
- 👤 Leading actors  
- 🗳️ Number of votes

## ✨ Features

- **Data Exploration** 🔍: Examines distributions, trends, and missing values within the dataset.
- **Data Preprocessing** 🧹: Handles missing values and prepares categorical attributes (genre, director, cast) with appropriate encoding for model input.
- **Feature Engineering** 🛠️: Includes techniques like numerically encoding directors/actors, generating metrics such as genre mean rating, and creating new indicator variables.
- **Modeling** 🤖: Applies regression algorithms (e.g., linear regression) to predict the movie's rating from its features.
- **Evaluation** 📊: Assesses model performance on a held-out test set, analyzing which features most influence predictions.

## 🛠️ Technologies Used

- 🐍 Python  
- 🐼 pandas for data processing  
- 🔗 scikit-learn for machine learning algorithms  
- 📒 Jupyter Notebook for development and visualization

## 🎲 Dataset

The dataset file `IMDb_Movies_India.csv` consists of thousands of movie records, each with details including:

| Feature   | Description                                |
|-----------|--------------------------------------------|
| Name      | Movie title                                |
| Year      | Year of release                            |
| Duration  | Movie duration in minutes                  |
| Genre     | Genre categories (Drama, Action, etc.)     |
| Rating    | IMDb or similar movie rating               |
| Votes     | Number of user ratings                     |
| Director  | Name of the director                       |
| Actor 1   | Main actor                                 |
| Actor 2   | Supporting actor                           |
| Actor 3   | Additional leading actor                   |

## 🚀 How to Use

1. 🧬 Clone the repository.
2. 📦 Install required packages: `pandas`, `scikit-learn`, `jupyter`.
3. 💻 Launch the Jupyter notebook `Movie_rating_prediction.ipynb` to explore the data, train the model, and view the results.
4. 🚧 Enhance the solution by experimenting with different models or advanced feature engineering techniques.

---

This project demonstrates practical machine learning on real-world data, emphasizing data cleaning, feature engineering, and model evaluation for those interested in predictive analytics within the entertainment domain. :star2:

---

If you find this project useful, please ⭐ the repository!
