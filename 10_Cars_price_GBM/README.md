# Прогнозирование стоимости автомобиля для продажи

Теги: #preprocessing #gradientboost #execution_time #regression #optimization

Целью работы было определение оптимальной модели для предсказания цены автомобиля по данным из объявлений о прожаже. 
Критерии оценки моделей:
+ качество предсказания (RMSE)
+ скорость предсказания
+ время обучения

Входными данными была выгрузка объявлений о продаже автомобилей (около 300к записей).

**Задачи и этапы исследования:**
1. Предобработка данных (очистка, форматирование, обработка пропусков)
2. Анализ данных на наличие аномалий
3. Определение и подготовка признаков для обучения моделей
4. Подготовка критериев оценки моделей
5. Обучение моделей, поиска оптимальных гипер-параметров (Grid_search + Cross Validation)
6. Валидация, тестирование и оценка полученных моделей
7. Формулирование выводов

**Используемые инстументы\библиотеки:**
- pandas
- numpy
- seaborn
- matplotlib
- scipy
- sklearn
- xgboost
- lightgbm
- catboost
- %timeit
