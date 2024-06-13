# Video People Detection Project
Этот проект выполняет детекцию людей на видео с использованием предобученной модели RetinaNet.

## Структура проекта:
```
BBN_LLC_TZ/
│
├── detector_Cascade_R-CNN.py
├── detector_retinaNet.py
├── requirements.txt
├── Выводы.docx
├── README.md
└── video/
    ├── reference_on_video_result.txt(ссылка на диск с результатами)
```
    
## Установка
1. Склонируйте репозиторий.
    ```bash
    git clone https://github.com/Ruziy/BBN_LLC_TZ
    cd BBN_LLC_TZ
    ```
2. Установите необходимые библиотеки:
    ```bash
    pip install -r requirements.txt
    ```

## Использование

1. Поместите входное видео в папку `video` и назовите его `crowd.mp4`.
2. Запустите скрипт на выбор detector_retinaNet.py/detector_Cascade_R-CNN.py:
    ```bash
    python detector_retinaNet.py
    ```
3. Обработанное видео будет сохранено в папке `video` под названием `output_crowd.mp4`.
4. Общее количество распознанных людей будет выведено в консоль.
