# 🎓 Udemy Course Analysis & Prediction: Insights into Online Learning  

## 📌 Project Overview  
This project explores a **Udemy courses dataset (13,608 records, 20 attributes)** to analyze online learning patterns.  
The aim is to understand **course popularity, pricing strategies, ratings, and learner engagement**,  
and to build predictive models to identify key factors that drive **course success**.  

---

## 🎯 Objectives  
1. **Data Exploration**  
   - Explore course attributes (title, category, pricing, number of subscribers, ratings, reviews, lectures, tests).  
   - Understand trends in learner engagement and instructor strategies.  

2. **Visualization**  
   - Build charts to show popularity trends (subscribers, reviews).  
   - Compare free vs. paid courses, ratings distributions, and pricing structures.  

3. **Insights & Recommendations**  
   - Identify factors driving course success (high subscribers & ratings).  
   - Highlight the role of pricing, reviews, and content volume in learner engagement.  
   - Suggest strategies for instructors to design better-performing courses.  

4. **(Optional Extension – ML)**  
   - Train machine learning models to predict course popularity based on attributes.  
   - Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.  

---

## 📊 Dataset  
- **Source:** Udemy Course Dataset (13,608 courses)  
- **Records:** 13,608 rows  
- **Features:** 20 attributes covering course details, pricing, reviews, and ratings  
- **Missing Values:** Minimal / manageable  

### Key Columns  
- **title, url** → course details  
- **is_paid, discount_price__amount, price_detail__amount** → pricing & monetization  
- **num_subscribers, num_reviews, is_wishlisted** → engagement metrics  
- **avg_rating, avg_rating_recent, rating** → learner satisfaction  
- **num_published_lectures, num_published_practice_tests** → content volume  
- **created, published_time** → timeline of course publication  

---

## 🔍 Project Steps  
1. **Data Overview** – dataset structure, descriptive statistics, missing values  
2. **Exploratory Data Analysis (EDA)** –  
   - Distribution of subscribers, reviews, and ratings  
   - Paid vs free course comparison  
   - Price vs rating/subscriber trends  
3. **Visualizations** –  
   - Top 10 courses by subscribers  
   - Ratings distribution  
   - Subscribers vs. reviews scatter plot  
   - Pricing vs. popularity trend  
   - Content volume (lectures/tests) vs success  
4. **Insights** – interpret learner behavior and instructor strategies  
5. **(Optional ML Extension)** – predict course success/popularity  
6. **Recommendations** – for pricing, content design, and engagement improvement  
7. **Conclusion** – summarize findings and business implications  

---

## 💡 Key Insights  
- Most Udemy courses are **paid**, but free courses attract a large number of learners.  
- Courses with **higher subscriber counts** usually also have **higher review counts**, confirming reviews as a strong engagement proxy.  
- **Pricing is not the sole driver of success** — many moderately priced courses outperform expensive ones due to better ratings.  
- **Average ratings** cluster between 4.2 – 4.7, showing most learners are generally satisfied.  
- **Course length (lectures/tests)** impacts engagement, but quality (ratings) matters more than sheer volume.  

---

## 🏆 Conclusion  
This analysis reveals that **learner engagement on Udemy is influenced more by course quality and relevance than price**.  
Key strategies for course creators include:  
- Focus on maintaining high **average ratings** through engaging and updated content.  
- Leverage **reviews and wishlists** as strong indicators of popularity.  
- Keep pricing competitive; free courses can be effective for reach but paid courses sustain revenue.  
- Balance **content length with quality**; more lectures don’t always mean better success.  

A machine learning extension demonstrated that course features (ratings, reviews, pricing, content) can predict course popularity with reasonable accuracy.  

---

## 🚀 How to Run  
You can run the notebook directly in **Google Colab**:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amitkumarbhade/Udemy_Course_Analysis_And_Prediction/blob/main/Udemy_FA_Course_Prediction.ipynb)  

Steps:  
1. Upload the notebook (`Udemy_FA_Course_Prediction.ipynb`) to Colab.  
2. Upload the dataset file (`FA_Udemy.csv`) when prompted.  
3. Run cells sequentially to reproduce the analysis and visualizations.  

---
