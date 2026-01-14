# 📊 Google Play Store Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Google Play Store dataset to understand:
- App distribution across categories
- Relationship between ratings, installs, size, and pricing
- Differences between free and paid apps
- Category-wise behavior from a business perspective

The goal is to extract **meaningful insights** that can help developers and businesses make informed decisions.

---

## 📂 Dataset
- Source: Google Play Store dataset (Kaggle)
- Key columns used:
  - App
  - Category
  - Rating
  - Reviews
  - Size
  - Installs
  - Type (Free / Paid)
  - Price
  - Content Rating

---

## 🧹 Data Cleaning & Preprocessing
The following steps were performed before analysis:

- Removed duplicate apps
- Handled missing values:
  - **Rating & Size** → Filled using **category-wise median** to avoid cross-category bias
  - Other columns with negligible nulls → Filled using mode
- Converted:
  - Size to numeric values (MB)
  - Installs to integer format
  - Price to numeric
- Ensured dataset consistency for analysis

---

## 📊 Exploratory Data Analysis
Key analyses performed include:

- Distribution of apps across categories
- Rating distribution and trends
- App size variation by category
- Relationship between installs and ratings
- Comparison between free and paid apps
- Category-wise behavioral patterns

Visualizations used:
- Bar charts
- Histograms
- Box plots
- Scatter plots

---

## 💡 Key Insights
- Most apps on the Play Store are **compact in size**
- **Games and Family** categories have the **largest and most variable app sizes**
- Free apps dominate the platform in volume
- Paid apps tend to have **slightly higher ratings**, but fewer installs
- High installs do not always guarantee high ratings
- App behavior varies significantly by category

---

## 📈 Business Takeaways
- New developers should:
  - Focus on compact apps
  - Prefer free pricing models
  - Target high-volume categories
- Established developers can:
  - Build larger, feature-rich apps
  - Target Games and Family categories
  - Monetize through paid models or in-app purchases

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---


