# Video People Detection Project
Этот проект выполняет детекцию людей на видео с использованием предобученной модели RetinaNet.

## Структура проекта:
my_project/
│
├── main.py
├── requirements.txt
├── README.md
└── video/
    ├── crowd.mp4
    └── output_crowd.mp4
    
## Установка
1. Склонируйте репозиторий.
2. Установите необходимые библиотеки:
    ```bash
    pip install -r requirements.txt
    ```

## Использование

1. Поместите входное видео в папку `video` и назовите его `crowd.mp4`.
2. Запустите скрипт:
    ```bash
    python main.py
    ```
3. Обработанное видео будет сохранено в папке `video` под названием `output_crowd.mp4`.
4. Общее количество распознанных людей будет выведено в консоль.
