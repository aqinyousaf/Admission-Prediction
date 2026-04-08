[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)](https://www.python.org/)
[![Model](https://img.shields.io/badge/Model-Linear%20Regression-orange)](#)

A machine learning web application that predicts a student's chance of admission to graduate school based on academic and profile metrics. The model was trained on historical admissions data and deployed as an interactive website for easy demonstration.

## 📸 Preview

![App Screenshot](screenshot.png)
![App Screenshot (1)](screenshot1.png)

> *Click the "Live Demo" badge above to try it yourself!*

## 🚀 Features

- **Interactive Sliders:** Adjust GRE, TOEFL, CGPA, and more.
- **Real-time Prediction:** Logistic/Linear Regression model runs entirely in the browser.
- **Business-Friendly Output:** Plain-English advice alongside percentage scores.
- **Input Validation:** Prevents unrealistic values from skewing results.
- **Fully Responsive:** Works on desktop, tablet, and mobile.

## 📊 The Model

| Metric | Value |
|--------|-------|
| Algorithm | Linear Regression |
| Features | GRE, TOEFL, University Rating, SOP, LOR, CGPA, Research |
| R² Score | [e.g., 0.77] |
| MAE | [e.g., 0.06] |

**Key Insight:** CGPA was the strongest predictor, while Statement of Purpose showed minimal impact in this dataset.

## 🛠️ Technologies Used

- **Python:** scikit-learn, pandas, numpy (Training)
- **JavaScript:** Model deployment in browser
- **HTML/CSS:** Frontend interface
- **GitHub Pages:** Hosting

## 📁 Repository Structure
