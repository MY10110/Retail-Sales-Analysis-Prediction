# Sales Analysis & Prediction

### 📌 Project Overview

This project takes raw retail sales data and transforms it into actionable insights and a working sales prediction tool.
I handled the entire process — from cleaning and exploring the data to building a predictive machine learning model and visualizing the results.

### Note:

This repository contains two versions of the notebook — one with Plotly visuals and another using Matplotlib and Seaborn for static plots. Plotly visuals and the saved prediction model (.pkl file) won’t display or run directly on GitHub. Please download the notebook(s) and model files to run the dashboard and predictions locally.

### Sales Prediction Dashboard

<img width="1457" height="756" alt="Screenshot 2025-08-10 210137" src="https://github.com/user-attachments/assets/970def33-201b-4de6-b4b4-6ccc2d4e7434" />

### 🎯 Objectives

1. In this analysis, I set out to answer:

2. What kind of products sell more and which ones sell less?

3. Does the type of outlet or its age affect sales?

4. Do item features like fat content, weight, or type influence sales?

5. Can we build a reliable model to predict sales?

6. Which features matter most when predicting sales?

### 🔍 Key Findings

  • Top-selling categories: Household, Fruits & Vegetables, Snack Foods

  • Lowest sales: Seafood, Breakfast, Hard Drinks

  • Outlet effect: Supermarket Type3 had the highest sales; Grocery Stores the lowest

  • Outlet age: Medium-aged outlets performed best

  • Feature impact: Outlet Type, Item MRP, and Item Type were the strongest predictors

### 🤖 Machine Learning
  
  • Model Used: Gradient Boosting Regressor (best accuracy)

  • Outcome: Accurately predicts sales based on product and outlet details

  • Pipeline: Preprocessing + Model saved for future use

### 📊 Tools & Libraries

  • Python (Pandas, NumPy, Scikit-learn)

  • Matplotlib / Seaborn / Plotly for visualization

  • Dash for interactive prediction interface
