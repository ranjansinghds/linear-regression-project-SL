# E-Commerce Customer Analysis & Predictive Modeling
## Overviews
Welcome to the **E-Commerce Customer Analysis & Predictive Modeling** project! 🚀 This project explores customer behavior through data visualization and predictive modeling, helping us understand what drives customer spending. 

---

## 📊 Exploratory Data Analysis (EDA)

### 1️⃣ Time on Website vs. Yearly Amount Spent
Unlike the app, **time on the website does not strongly correlate with spending**. This suggests improving the website may not significantly impact revenue, while the app experience holds greater potential.

![Time on Website vs Yearly Amount Spent](https://github.com/ranjansinghds/linear-regression-project-SL/blob/main/Linear%20Regression%20Project%20PNG/Time%20on%20website%20vs%20Yearly%20Amount%20Spent.png)

### 2️⃣ Time on App vs. Yearly Amount Spent
We see a **positive correlation** between time spent on the app and yearly spending. Investing in the app experience could drive higher revenue!

![Time on App vs Yearly Amount Spent](https://github.com/ranjansinghds/linear-regression-project-SL/blob/main/Linear%20Regression%20Project%20PNG/Time%20on%20App%20vs%20Yearly%20Amount%20Spent.png)

### 3️⃣ Time on App vs. Length of Membership
A hexbin plot shows the density of data points. Customers who spend more time on the app are not necessarily long-term members, meaning **app engagement doesn't directly correlate with loyalty.**

![Time on App vs Length of Membership](https://github.com/ranjansinghds/linear-regression-project-SL/blob/main/Linear%20Regression%20Project%20PNG/Time%20on%20App%20vs%20Length%20of%20Membership.png)

### 4️⃣ Pairplot - Feature Correlations
A pairplot helps us visualize relationships between different numerical variables. From this, we can see which features have strong correlations with **Yearly Amount Spent**, hinting at key predictors.

![Pairplot of all features](https://github.com/ranjansinghds/linear-regression-project-SL/blob/main/Linear%20Regression%20Project%20PNG/Pairplot%20of%20all%20features.png)

### 5️⃣ Length of Membership vs. Yearly Amount Spent
One of the strongest correlations! Customers with longer memberships tend to spend more yearly. This insight suggests **loyalty programs** could be a major driver for revenue growth.

![Length of Membership vs Yearly Amount Spent](https://github.com/ranjansinghds/linear-regression-project-SL/blob/main/Linear%20Regression%20Project%20PNG/Length%20of%20Membership%20vs%20Yearly%20Amount%20Spent.png)

### 6️⃣ Model Performance - Predicted vs. Actual
Here, we compare our model's predictions to the actual test values. A strong **diagonal alignment** confirms our model is performing well!

![Model Performance](https://github.com/27abhishek27/Linear-Regression-Project/blob/main/Linear%20Regression%20project%20png/scatterplot%20of%20the%20real%20test%20values.png)

### 7️⃣ Histogram of Residuals
This histogram visualizes the residuals from our linear regression model, showing how well our model fits the data. A normal distribution indicates a good model fit, whereas skewness may suggest underlying patterns the model hasn't captured.

![Histogram of Residuals](https://github.com/27abhishek27/Linear-Regression-Project/blob/main/Linear%20Regression%20project%20png/histogram%20of%20the%20residuals.png)

---

## 🔢 Interpreting the Coefficients
- Holding all other features fixed, a **1 unit increase in Avg. Session Length** is associated with an **increase of $25.98** in total dollars spent.
- Holding all other features fixed, a **1 unit increase in Time on App** is associated with an **increase of $38.59** in total dollars spent.
- Holding all other features fixed, a **1 unit increase in Time on Website** is associated with an **increase of just $0.19** in total dollars spent.
- Holding all other features fixed, a **1 unit increase in Length of Membership** is associated with an **increase of $61.27** in total dollars spent.

---

## 📌 Business Insights & Recommendations
💡 **Should the company focus more on the mobile app or the website?**

This is a tricky question! There are two ways to think about it:
1. **Improve the website** to catch up to the performance of the mobile app.
2. **Double down on the mobile app**, since it already drives more revenue.

The best decision depends on additional factors, such as customer feedback and engagement metrics. It may be useful to explore the relationship between **Length of Membership and Time on App vs. Time on Website** before finalizing a strategy!

---

## 🤖 Key Takeaways
✅ **Length of membership is the best predictor** of yearly spending.
✅ **Time on the app is more important than time on the website** for increasing revenue.
✅ **Our predictive model performs well**, as shown by the residual histogram and test value scatterplot.
✅ **Focusing on customer loyalty programs and app engagement** could drive business growth.