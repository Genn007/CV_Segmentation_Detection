# Задача сегментирования изображения

Различные блокноты и py-файлы для задачи сегментирования изображений.  Суть задачи: 
- Приобретение опыта формирования модели сегментации изображений на PyTorch.
- Доведение учебного примера до приемлемого уровня за счет валиадационной выборки и метрик оценки качества модели. 

Датасет взят на [kaggle](https://www.kaggle.com/datasets/tapakah68/segmentation-full-body-mads-dataset/code). 

Прототип модели взят из [урока М.Горохова](https://github.com/magorokhoov/youtube_pytorch_lessons/tree/main/lesson_9)

Основные доработки: 
- валидационный датасет с правильной аугментацией;
- метрики качества при обучении;
- визуализация результата работы модели. 
