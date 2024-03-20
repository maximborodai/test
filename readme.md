# Задание для позиции "Программист-стажер в области Аналитики Больших данных и Искусственного интеллекта"

Была построена модель прогнозирования продаж, которая учитывает день недели и акцию.

В результате экспериментов была выбрана модель XGB Regression.

RMSE на тестовых данных (декабрь 2023) c использованием XGBRegressor (best): 14.4483.

Поля jan_2024_pred.csv:
* date - дата прогноза
* item_id - Код товара
* prediction - Количество товара (дробное число)

Прогнозы в файле jan_2024_pred.csv.

Разделитель в файле ';'.

Ссылка на решение в colab (на всякий случай):
https://colab.research.google.com/drive/1r1Xj4Li1cLsqV2TU3otT3-M2CKixP2uA?usp=sharing

Предсказания на январь 2024 в сравнении с реальными данными за январь 2023:

![image](https://github.com/maximborodai/test/assets/96576515/e372a058-1abb-4efc-a334-06240d62ccf9)
