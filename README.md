# Решение задачи классификации: определение вероятности наличия у объекта определенного класса.

## Описание проекта
### Решение содержит в папке vk_ds следующие файлы:
***experiment.ipynb*** - содержит в себе подробный анализ данных, построение выборок и обучение моделей.

***func_for_test.ipynb*** - содержит в себе функцию для быстрой обработки тестовой выборки.

***final_script.ipynb*** - содержит в себе скрипт, по итогам которого создается файл submission.csv

***c_model_t*** - модель машинного обучения CatBoost с наилучшими параметрами, которые были получены в ходе эксперимента.

***dt_model_f*** - модель машинного обучения RandomForestClassifier с наилучшими параметрами, но которая немного уступила в показателях CatBoost.


## Запуск

Для запуска итогового скрипта необходимо открыть файл ***final_script.ipynb***. После этого необходимо выполнить код в каждой из предоставленных ячеек: их всего 7.

В случае отсутствия определенных библиотек при инициализации ***notebool*** выполонить команду:

```rb
pip install -r requirements.txt
```

