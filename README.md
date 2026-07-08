# Customer Churn Prediction | Прогноз оттока клиентов

> 🇬🇧 English version is followed by the Russian version.

---

# 🇬🇧 English

## Project Overview

This project focuses on predicting customer churn for a telecommunications company using machine learning.

The objective is to determine whether a customer is likely to leave the company (`Churn = Yes`) based on demographic information, account details, and service usage.

The project covers the complete machine learning workflow:

- Data loading
- Exploratory Data Analysis (EDA)
- Data cleaning
- Feature Engineering
- Data preprocessing
- Model training
- Hyperparameter tuning
- Model evaluation
- Feature importance analysis

---

## Dataset

The dataset contains information about telecom customers, including:

- Customer demographics
- Contract information
- Internet and phone services
- Payment methods
- Monthly and total charges
- Customer churn (target variable)

**Target variable**

- `Churn`
    - Yes
    - No

---

## Project Structure

```
churn-final.ipynb    # Complete ML pipeline
README.md            # Project description
```

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost (if used)
- CatBoost (if used)

---

## Workflow

1. Import libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Detect missing values
5. Analyze numerical and categorical features
6. Perform Feature Engineering
7. Encode categorical variables
8. Scale numerical features (if required)
9. Split the data into train and test sets
10. Train multiple machine learning models
11. Tune hyperparameters
12. Compare model performance
13. Evaluate the best model
14. Analyze feature importance

---

## Evaluation Metrics

The models are evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

---

## Results

The notebook compares several machine learning algorithms and selects the best-performing model based on evaluation metrics.

Feature importance is also analyzed to identify which customer characteristics have the greatest impact on churn prediction.

---

## Author

Arif Babayev

---

# 🇷🇺 Русская версия

## Описание проекта

Проект посвящён прогнозированию оттока клиентов телеком-компании с использованием методов машинного обучения.

Цель работы — определить, уйдёт ли клиент из компании (`Churn = Yes`) на основе информации о клиенте, его тарифе и используемых услугах.

В проекте реализован полный цикл разработки модели машинного обучения:

- загрузка данных;
- разведочный анализ данных (EDA);
- очистка данных;
- Feature Engineering;
- предобработка данных;
- обучение моделей;
- подбор гиперпараметров;
- оценка качества моделей;
- анализ важности признаков.

---

## Датасет

Используется набор данных с информацией о клиентах телеком-компании.

Основные группы признаков:

- демографические данные;
- информация о договоре;
- подключённые услуги;
- способ оплаты;
- ежемесячные и общие платежи;
- факт ухода клиента.

**Целевая переменная**

- `Churn`
    - Yes
    - No

---

## Структура проекта

```
churn-final.ipynb    # Полный ML-пайплайн
README.md            # Описание проекта
```

---

## Используемые технологии

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost (если используется)
- CatBoost (если используется)

---

## Этапы работы

1. Импорт библиотек
2. Загрузка данных
3. Проведение EDA
4. Проверка пропусков
5. Анализ числовых и категориальных признаков
6. Feature Engineering
7. Кодирование категориальных признаков
8. Масштабирование данных (при необходимости)
9. Разделение выборки на train/test
10. Обучение нескольких моделей
11. Подбор гиперпараметров
12. Сравнение моделей
13. Оценка лучшей модели
14. Анализ важности признаков

---

## Метрики качества

Для оценки моделей используются:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

---

## Результат

В ноутбуке сравниваются несколько алгоритмов машинного обучения, после чего выбирается модель с наилучшими показателями качества.

Дополнительно проводится анализ важности признаков, позволяющий определить факторы, наиболее сильно влияющие на вероятность ухода клиента.

---

## Автор

Arif Magamedov
