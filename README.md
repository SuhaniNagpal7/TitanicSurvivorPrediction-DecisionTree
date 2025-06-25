# 🚢 Titanic Survivor Prediction using Decision Trees

A comprehensive machine learning project that predicts Titanic survivors using both **custom-built Decision Tree algorithms** and **scikit-learn implementations**. This project demonstrates the mathematics behind decision trees through custom entropy and information gain calculations.

## 🎯 Project Overview

This project tackles the famous Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic), implementing decision tree algorithms from scratch and comparing them with scikit-learn's optimized version. The goal is to predict passenger survival based on various features like age, gender, ticket class, and more.

### 🔑 Key Features

- ✨ **Custom Decision Tree implementation** with entropy calculations  
- 🔧 **Information Gain** computation from scratch  
- 📊 **Comprehensive data preprocessing and feature engineering**  
- 🚀 **Scikit-learn implementation** for comparison  
- 📈 **Detailed performance analysis** and accuracy evaluation  

---

## Algorithm

### Custom Implementation:

-**Entropy calculation**: Entropy(S) = -Σ(p_i * log₂(p_i))
-**Information Gain**: IG = Entropy(Parent) - Σ(|S_v|/|S| * Entropy(S_v))
-Recursive tree building with optimal feature splits

# Requirements

-pandas
-numpy
-scikit-learn
-matplotlib
