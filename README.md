# Lung Cancer Prediction: A Look into Lifestyles | 肺癌風險預測與生活型態分析

This project utilizes machine learning to predict lung cancer risk by analyzing a wide array of lifestyle factors. Moving beyond traditional risks like smoking, we explore modern behavioral data (Social Media, Online Gaming) to build high-accuracy predictive models using SVM, KNN, and Artificial Neural Networks (ANN).
本專案利用機器學習分析多樣化的生活型態因子來預測肺癌風險。除了傳統的吸菸因素外，我們更深入探討了現代行為（如社群媒體使用、線上遊戲）與健康的關係，並透過比較 SVM、KNN 與人工神經網路（ANN）建立高準確度的預測模型。

> **人工智慧與商業應用課程專案 · AI Business Final Project · 2023 · 第八組**

---

## 🎯 Objective | 分析目標
The primary goal is to identify which lifestyle habits contribute most significantly to lung cancer risk. By leveraging AI, we aim to provide an early-warning diagnostic tool that achieves high precision and recall, especially in identifying high-risk individuals who may not be traditional smokers.
核心目標是識別哪些生活習慣對肺癌風險影響最顯著。透過 AI 技術，我們旨在開發一個具備高精準度與召回率的預警工具，特別是針對非傳統吸菸族群的高風險預測。

---

## 🛠 Pipeline | 處理流程
1. **Data Preprocessing:** Handling categorical data via One-Hot encoding and addressing class imbalance. / 資料前處理：透過 One-Hot 編碼處理類別資料，並優化類別不平衡問題。
2. **Exploratory Data Analysis (EDA):** Visualizing correlations between 25+ features including air pollution, alcohol use, and digital habits. / 探索性資料分析：分析包含空氣污染、飲酒及數位習慣在內的 25 個以上特徵之關聯性。
3. **Model Training & Comparison:** Implementing and fine-tuning three distinct architectures:
    * **SVM (Support Vector Machine):** Used for feature impact analysis.
    * **KNN (K-Nearest Neighbors):** Achieving 96.59% accuracy after removing SMOTE.
    * **ANN (Artificial Neural Network):** Optimized with Softmax activation and threshold adjustment (Accuracy: 0.9133).
4. **Insight Extraction:** Analyzing model coefficients to identify unexpected risk drivers. / 洞察萃取：分析模型係數，找出非典型的風險驅動因子。

---

## 💻 Tech Stack | 技術棧
* **Models:** SVM, KNN, Artificial Neural Networks (ANN)
* **Libraries:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn
* **Activation Functions:** Softmax, ReLU
* **Evaluation Metrics:** Accuracy, Recall, Precision, F1-Score

---

## 📊 Key Findings | 核心洞察
* **Top Risk Drivers:** Beyond **Smoking** (which remains the leading cause), the models identified **Social Media** and **Online Gaming** as significant indirect indicators, likely linked to sedentary lifestyles and unhealthy coping mechanisms. / 核心風險因子：除了首要原因「吸菸」外，模型發現「社群媒體」與「線上遊戲」是重要的間接指標，這可能與久坐生活及心理壓力引發的不健康習慣有關。
* **Irrelevant Factors:** Interestingly, **Gender** showed minimal impact on lung cancer risk in this specific dataset. / 無關因子：有趣的是，在此數據集中，「性別」對肺癌風險的影響極小。
* **Model Performance:** **KNN** yielded the highest final accuracy of **96.59%**, while **ANN** with Softmax activation provided the best overall predictive balance after threshold adjustment. / 模型表現：KNN 達成了最高的 96.59% 準確度；而經過閾值調整後的 ANN 模型則在綜合預測表現上最為平衡。

---

## 👥 Team Members | 團隊成員
* **黃筠茜 (Athena Huang):** EDA & Model Training / 探索性分析與模型訓練
* **連姵涵:** Lung Cancer Research & Design / 肺癌研究與設計
* **蕭米柔:** Presentation / 簡報呈現
* **陳致宇:** Data Processing / 資料前處理
* **徐嘉妤:** EDA & Model Training / 探索性分析與模型訓練
* **Jerzy Kopinski:** Model Training / 模型訓練
* **Lina Maria Krueger:** Presentation / 簡報呈現

---

## 中文簡介
本專案為「人工智慧與商業應用」課程期末專案。我們針對全球死亡率最高的肺癌進行風險預測研究。除了傳統已知的風險因子（如吸菸、空氣污染）外，專案特別關注現代人的數位生活習慣（社群媒體、線上遊戲）與肺癌的關聯性。我們實作並比較了 SVM、KNN 與 ANN 三種模型，其中 KNN 在優化後達到了 96.59% 的高準確度。分析結果顯示，生活習慣（Lifestyle）與習慣性行為可能是肺癌風險的重要根源，這為預防醫學與健康管理提供了新的 AI 觀察視角。
