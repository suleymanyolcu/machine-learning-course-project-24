# 🏀 NBA Injury Prediction: A Data-Driven Approach

## 📚 Project Overview
This project explores the development of a machine-learning model to predict NBA player injuries. By combining historical injury records with detailed player performance metrics, the project identifies patterns and risk factors contributing to injury risk. The goal is to help teams make informed decisions regarding player workload management, recovery protocols, and injury prevention strategies.

## 📊 Dataset
- **Historical Injury Data (2010–2020):** Documenting injury types, affected body regions, and severity.
- **Player Performance Data (2013–2023):** Including metrics such as minutes played, points scored, and average workload per game.

**Dataset Sources:**
- [NBA Injury Dataset (2010–2020)](https://www.kaggle.com/datasets/ghopkins/nba-injuries-2010-2018)
- [NBA Player Stats Dataset (2013–2023)](https://www.kaggle.com/datasets/icliu30/nba-player-stats-and-injured-data-from-13-to-23)

## 📝 Blog Posts
This project has been documented across multiple blog posts on Medium:
1. [Predicting NBA Player Injuries: A Data-Driven Approach](https://medium.com/ain311-fall-2024-projects/predicting-nba-player-injuries-a-data-driven-approach-aa406d0aa9a0)
2. [Exploring NBA Injury Data & Preprocessing](https://medium.com/ain311-fall-2024-projects/ain-311-machine-learning-blog-2-exploring-nba-injury-data-preprocessing-f8963af8b2f4)
3. [Analyzing Injury Trends and Initial Modeling](https://medium.com/ain311-fall-2024-projects/ain-311-machine-learning-blog-3-analyzing-injury-trends-and-initial-modeling-ba35bcedee77)
4. [Advanced Modeling and Feature Importance](https://medium.com/ain311-fall-2024-projects/ain-311-machine-learning-blog-4-advanced-modeling-and-feature-importance-573c3560c25f)
5. [Enhancing Model Performance through Cross-Validation](https://medium.com/ain311-fall-2024-projects/ain-311-machine-learning-blog-5-enhancing-model-performance-through-cross-validation-and-540d52568ae1)

---

## ⚙️ Methodology

### 📌 **Data Preprocessing**
- Cleaned historical injury data to remove non-relevant entries.
- Standardized player performance metrics.
- Merged injury data and player stats into a unified dataset.

### 📊 **Exploratory Data Analysis (EDA)**
- Analyzed injury distribution by type, body region, and season.
- Identified correlations between workload metrics and injury occurrences.

### 🤖 **Model Training**
- Implemented and evaluated multiple classification algorithms:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - K-Nearest Neighbors (kNN)
   - Support Vector Machine (SVM)

### 🔍 **Hyperparameter Tuning**
- Applied 5-Fold Cross-Validation for robust model evaluation.
- Fine-tuned parameters using Grid Search and Random Search.

---

## 📈 Results
- **Best Performing Model:** Random Forest
- **Key Metrics:** Accuracy: 94.97%, Precision: 91.49%, Recall: 90.34%, F1-Score: 90.91%
- **Feature Importance:** Metrics like minutes played, workload, and anthropometric attributes significantly influence injury predictions.

---

## 📊 Reports
- **[Final Report](./Final_Report.pdf)**: Comprehensive analysis, methodology, and results of the project.
- **[Progress Report](./project_progress_report.pdf)**: Insights and updates during the project's development phase.

---

## 🚀 How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone <repo-link>
   cd nba-injury-prediction-ml
