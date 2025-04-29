# 📊 Google Play Store Apps - Exploratory Data Analysis (EDA)

This project analyzes data from the Google Play Store to uncover trends in app ratings, user engagement, download patterns, and monetization strategies. The goal is to identify what drives app popularity and how developers and marketers can use these insights to improve visibility and user satisfaction.

---

## 🔍 Objectives

- Analyze app ratings distribution.
- Investigate correlation between downloads and ratings.
- Compare performance across different app categories.
- Study differences between Free and Paid apps.
- Understand pricing and content rating trends.
- Explore the impact of app size on rating/popularity.

---

## 📁 Dataset

The dataset used is from the [Google Play Store](https://www.kaggle.com/datasets/lava18/google-play-store-apps) (Kaggle).

**Attributes include:**
- App name, Category, Rating
- Reviews, Installs, Size, Price
- Content Rating, Type (Free/Paid), etc.

---

## 🧹 Data Cleaning

- Converted `Reviews`, `Installs`, `Size`, and `Price` into numeric values.
- Removed or imputed missing values using median/mode.
- Standardized units (Size converted to KB).
- Handled special cases like "Varies with device".

---

## 📊 Key Insights

- Most apps have ratings between 4.0 and 4.7.
- Higher installs are loosely associated with better ratings.
- `GAME`, `TOOLS`, and `COMMUNICATION` are among top-performing categories.
- Free apps dominate the market but Paid apps have higher price ranges.
- Content rated "Everyone" is most common and widely downloaded.
- App size has minimal direct impact on rating.

---

## 📷 Visualizations

Includes:
- Rating Distribution
- Installs vs Ratings (Log Scale)
- Top Categories by Rating & Installs
- Free vs Paid Comparison
- Price Distribution of Paid Apps
- App Size vs Rating
- Content Rating Distribution

---

## 📌 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google Colab
