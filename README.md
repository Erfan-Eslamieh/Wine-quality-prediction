# 🍷 Wine Quality Prediction

Wine quality prediction is a crucial task in the wine industry as it helps **producers**, **sellers**, and **consumers** make informed decisions based on the wine's characteristics. This project aims to build **machine learning models** that predict wine quality using various **physicochemical features** such as acidity, alcohol content, pH level, and sulfur dioxide concentration.

We explore and compare the performance of different ML algorithms including **Logistic Regression**, **K-Nearest Neighbors (KNN)**, **Decision Trees**, and **Random Forests**, evaluating their ability to classify wine quality accurately.

---

## 📦 Project Structure

1. **Description of all columns in our dataset**  
   Understanding the meaning and importance of each feature.

2. **Import Libraries**  
   Importing essential libraries like `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`, `Scikit-learn`.

3. **Call Dataset**  
   Loading the Wine Quality dataset into the environment.

4. **Exploratory Data Analysis (EDA)** 🔍  
   - Handling missing values  
   - Visualizing distributions  
   - Analyzing correlations  

5. **Feature Engineering & Modeling** 🛠  
   - Feature scaling and normalization  
   - Squaring certain features  
   - Applying PCA (Principal Component Analysis)  
   - Cross-validation  

6. **Modeling** 🤖  
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
   - Random Forest  
   - Decision Tree (with and without entropy)

---

## 📊 Column Descriptions

| Feature                | Description |
|------------------------|-------------|
| `fixed acidity`        | Natural acids in wine (e.g., tartaric, malic) |
| `volatile acidity`     | Vinegar-like smell in wine |
| `citric acid`          | Enhances freshness and flavor |
| `residual sugar`       | Sugar remaining after fermentation |
| `chlorides`            | Salt content in wine |
| `free sulfur dioxide`  | Protects wine from oxidation and spoilage |
| `total sulfur dioxide` | Combined free and bound SO2 |
| `density`              | Weight per unit volume |
| `pH`                   | Acidity or alkalinity level |
| `sulphates`            | Added to preserve wine quality |
| `alcohol`              | Ethanol concentration in wine |
| `quality`              | Wine quality score (target variable) |

---

## 💡 Insights & Applications

- Higher **alcohol levels** generally correlate with better wine quality.
- Lower **volatile acidity** contributes to a more pleasant aroma and thus higher ratings.
- Wines with balanced **pH**, **sulphates**, and **citric acid** levels tend to perform better in terms of taste and shelf life.
- **PCA** can reduce feature complexity while preserving essential information for classification.

---

## 🏷️ Tags

`#WineQuality` `#MLClassification` `#RandomForest` `#LogisticRegression` `#KNN` `#EDA` `#PCA` `#WineIndustry`

---

## 🤝 Contribute

Feel free to **fork this repository**, raise **issues**, or submit **pull requests** to improve model accuracy, add new features, or experiment with other datasets and algorithms.


## 👨‍💻 **Author**

**Erfan Eslamieh**

M.Sc. in Cognitive Science – Specializing in Generative AI, Machine Learning, and Deep Learning  
📧 [erfan.cognitive.work@gmail.com]   
🔗 [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/erfan-eslamieh) [![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/erfaneslamieh)
