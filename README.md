# 🏡 House Prices Regression — Kaggle Advanced Regression Techniques

Этот проект представляет собой полноценный ML-пайплайн для задачи **предсказания стоимости жилья** по данным Kaggle:  
- [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)  
- [Housing Prices Competition for Kaggle Learn Users](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)  

Работа выполнена в формате end-to-end проекта и отражает ключевые навыки в Data Science и машинном обучении.  

---

## 📌 Цели проекта
- Построить модель регрессии для прогнозирования `SalePrice`.
- Реализовать полный ML-процесс: от обработки данных до ансамблирования моделей.
- Достичь высокой точности и подтвердить её результатами на Kaggle leaderboard.

---

## 🏆 Достижения
- **14 место из 5919 участников** в соревновании *Housing Prices Competition for Kaggle Learn Users*.  
- **Топ-11% (456 место из 4261 участников)** в соревновании *House Prices: Advanced Regression Techniques*.  

---

## 🔧 Использованные технологии
- **Python 3.10+**
- **Основные библиотеки**:  
  `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `optuna`  
  `xgboost`, `lightgbm`, `catboost`  

---

## 📊 Этапы проекта
1. **Загрузка и анализ данных**  
   - Первичный EDA, визуализация распределений и выбросов.  
   - Анализ корреляций и взаимосвязей признаков.  

2. **Предобработка данных**  
   - Обработка пропусков.  
   - Кодирование категориальных признаков.  
   - Масштабирование и нормализация.  

3. **Фичеринг (Feature Engineering)**  
   - Создание новых признаков.  
   - Отбор наиболее информативных фичей.  

4. **Моделирование**  
   - Базовые модели: Ridge, Lasso, ElasticNet.  
   - Градиентный бустинг: LightGBM, XGBoost, CatBoost.  
   - Ансамблирование: **Stacking + Blending**.  

5. **Оптимизация гиперпараметров**  
   - Байесовская оптимизация через **Optuna**.  

6. **Финальный сабмит**  
   - Подготовка `submission.csv` для Kaggle.  

---

