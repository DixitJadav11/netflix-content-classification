# netflix-content-classification
🎬 Netflix content classification project using logistic regression &amp; random forest with 99%+ accuracy.

# 🎬 Netflix Content Classification (Movie vs TV Show)

A machine learning project to classify Netflix content into Movies or TV Shows using metadata and content patterns.

## 📊 Dataset
- 8800+ entries
- Features: Title, Type, Duration, Country, Cast, Genres
- Binary target: is_movie (1=Movie, 0=TV Show)

## 🧹 Preprocessing & Feature Engineering
- Extracted: duration in minutes, genre flags, release decade
- One-hot encoded genres and countries
- Added NLP features: title_word_count, is_christmas, is_love

## ⚙️ Models Used
- Logistic Regression
- Random Forest

✅ Both models achieved 99–100% accuracy due to clear feature separation (`duration_int`)

## 📈 Feature Importance
- Top predictors: `duration_int`, genres, content type

## 📁 Files
- Full notebook + presentation + README

## 👨‍💻 Author
**Dixit Jadav**  
[LinkedIn](https://www.linkedin.com/in/dixit-jadav)

