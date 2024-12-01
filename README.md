# Поиск подозрительных транзакций


    project/
    │
    ├── load_data.py          # Модуль для загрузки и обработки данных
    ├── eda.py                # Модуль для первичного анализа данных (EDA)
    ├── train_model.py        # Модуль для обучения модели
    ├── predict.py            # Модуль для предсказаний и сохранения результатов
    ├── visualize.py          # Модуль для визуализации результатов
    ├── main.py               # Главный файл для запуска программы
    ├── utils.py              # Утилиты, включая сохранение/загрузку моделей
    └── dataset/              # Папка для данных
        ├── dataset.csv       # Исходный набор данных
        └── preds.csv         # Результаты предсказаний
