<div align="center">

# 🎬 Movie Box Office Revenue Prediction

### *Predicting Financial Success in Cinema with Machine Learning*

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

**End-to-end data science project** analyzing 63,000+ movies to predict box office revenue and uncover the key drivers of financial success in the film industry.

[View Notebook](DataScienceMovies.ipynb)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Results](#-key-results)
- [Dataset](#-dataset)
- [Machine Learning Pipeline](#-machine-learning-pipeline)
- [Key Insights](#-key-insights)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Enhancements](#-future-enhancements)

---

## 🎯 Overview

This project showcases a complete machine learning workflow for predicting movie box office revenue. Using real-world data, it demonstrates proficiency in:

- **Data Wrangling**: Cleaning and preprocessing 63,000+ movie records
- **Feature Engineering**: Transforming raw data into predictive features
- **Exploratory Analysis**: Uncovering patterns and relationships in the data
- **Model Development**: Building and comparing multiple ML algorithms
- **Model Interpretation**: Understanding feature importance and business impact

> **Goal**: Predict movie revenue and identify what drives box office success

---

## 🏆 Key Results

<div align="center">

### **R² Score: 0.81** | **Best Model: Random Forest Regressor**

</div>

The final model explains **81% of variance** in movie revenue on unseen test data, significantly outperforming baseline approaches.

**Performance Metrics:**
- **R² Score**: 0.81 (strong predictive power)
- **MAE**: Mean Absolute Error minimized
- **RMSE**: Root Mean Squared Error optimized

---

## 📊 Dataset

| Attribute | Details |
|-----------|---------|
| **Source** | Movie industry database |
| **Raw Size** | ~63,000 movies |
| **Cleaned Dataset** | 8,698 movies |
| **Features Used** | Budget, popularity, vote count, genre, language, runtime, release timing |

### Key Features:
- 💰 **Financial**: Budget & revenue
- 📈 **Engagement**: Vote count, popularity score
- 🎭 **Categorical**: Genre, language, production countries
- ⏱️ **Temporal**: Release date, runtime

---

## 🧠 Machine Learning Pipeline

### Problem Type
**Supervised Regression** - Predicting continuous revenue values

### Models Implemented

| Model | Type | Performance |
|-------|------|-------------|
| Baseline | Mean Predictor | Benchmark |
| Linear Regression | Linear Model | Good |
| Decision Tree | Tree-based | Better |
| **Random Forest** | **Ensemble** | **Best (R² = 0.81)** |

### Evaluation Strategy
- Train/test split validation
- Multiple evaluation metrics (R², MAE, RMSE)
- Feature importance analysis
- Model comparison framework

---

## 💡 Key Insights

### Top Predictors of Box Office Revenue:

1. **💵 Budget** - Strongest single predictor of revenue
2. **🔥 Popularity** - Audience engagement metrics highly predictive
3. **👥 Vote Count** - Community engagement signals success
4. **🎬 Genre** - Animation, Adventure, and Sci-Fi genres perform best

### Business Findings:

- ✅ **Quantitative features** (budget, popularity) outperform qualitative ones (genre)
- ✅ **Ensemble methods** (Random Forest) significantly outperform simple models
- ✅ **High-budget productions** benefit from economies of scale
- ✅ **Audience engagement** is a stronger signal than critical metrics

---

## 📂 Project Structure

```
movies-data-science/
│
├── DataScienceMovies.ipynb    # 📓 Main analysis & ML pipeline
├── movies.csv                 # 📁 Raw dataset
├── cleaned_movies.csv         # ✨ Cleaned dataset
└── README.md                  # 📖 Project documentation
```

---

## 🛠️ Technologies Used

### Core Stack
- **Python 3.8+** - Primary programming language
- **Jupyter Notebook** - Interactive development environment

### Libraries
| Category | Tools |
|----------|-------|
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | scikit-learn |

---

## 🚀 Skills Demonstrated

This project showcases the following data science competencies:

| Skill Category | Specific Skills |
|----------------|----------------|
| **Data Engineering** | ✔ Data cleaning & preprocessing<br>✔ Handling missing values & outliers<br>✔ Feature engineering & transformation |
| **Analysis** | ✔ Exploratory Data Analysis (EDA)<br>✔ Statistical analysis & visualization<br>✔ Pattern recognition |
| **Machine Learning** | ✔ Supervised learning (regression)<br>✔ Model selection & comparison<br>✔ Hyperparameter considerations |
| **Communication** | ✔ Clear documentation<br>✔ Data storytelling<br>✔ Actionable insights |

---

## 🔮 Future Enhancements

### Planned Improvements:

- [ ] **ROI Prediction** - Predict profitability instead of raw revenue
- [ ] **Advanced Features** - Incorporate cast, director, and marketing spend data
- [ ] **Gradient Boosting** - Experiment with XGBoost and LightGBM
- [ ] **Time-Based Validation** - Implement realistic temporal train/test splits
- [ ] **Deep Learning** - Explore neural network architectures
- [ ] **Deployment** - Create interactive web application for predictions

---

<div align="center">

## 📬 Contact & Portfolio

*This project was developed to demonstrate applied machine learning skills with real-world data.*

**Built with** ❤️ **for data-driven decision making**

</div>
