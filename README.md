# 🎵 Music Recommendation System using Machine Learning

## 📌 Project Overview
This project explores various machine learning models to enhance music recommendation systems. By analyzing user interaction data and song metadata, the system predicts the likelihood of song replay after an initial listen. The project evaluates multiple algorithms such as Decision Trees, Random Forests, CatBoost, and XGBoost to improve user engagement and satisfaction.

## 📂 Dataset
The model is trained on the *KKBOX music recommendation dataset*, which includes:
- train.csv - User interactions with songs, including user ID, song ID, and source type.
- songs.csv - Metadata of around 380,000 songs (length, genre, artist, etc.).
- members.csv - User demographics like age and gender.
- song_extra_info.csv - Additional song details like ISRC codes.

## 📊 Machine Learning Models Used
We experimented with the following models:
1. *CatBoost Classifier* (Best performing)
2. *XGBoost*
3. *LightGBM*
4. *Decision Tree*
5. *Random Forest*
6. *Gaussian Naïve Bayes*
7. *Logistic Regression*
8. *K-Nearest Neighbors (KNN)*
9. *K-Means Clustering*
10. *Support Vector Machine (SVM)*
11. *Agglomerative Clustering*
12. *Birch Clustering*

## 🏆 Best Performing Model
- *CatBoost Classifier (1000 iterations)*
  - Accuracy: *66.8%*
  - F1-score: *0.678*
  - Recall: *69.7%*

## 🔧 Installation & Setup
To run the project, follow these steps:

1. Clone the repository:
   bash
   git clone https://github.com/Hari-31/Music-Recommendation-project.git
   cd Music_Recommendation_ML
   

2. Install dependencies:
   bash
   pip install -r requirements.txt
   

3. Run the Jupyter Notebook:
   bash
   jupyter notebook Music_Recommendation_ML.ipynb
   

## 📈 Model Evaluation
We evaluated models using:
- *Accuracy*
- *Precision*
- *Recall*
- *F1-score*
- *Confusion Matrix Analysis*

## 🔮 Future Enhancements
- Implement *deep learning models* like RNNs and Transformers for better sequential learning.
- Improve feature engineering to extract richer insights from the data.
- Apply *hyperparameter tuning* for better performance.
- Address class imbalance with oversampling or cost-sensitive learning.

## 📝 Contributors
- *Satya Chandana Snehal Mattaparti*
- *Hari Krishna Reddy Padala*
- *Aishwarya Reddy Chinthalapudi*
- *Hamsini Pulugurtha*
