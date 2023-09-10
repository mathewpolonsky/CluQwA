# CluQwA: Clustering for Question Answering

![image](https://github.com/mathewpolonsky/CluQwA/assets/112184397/0e0afea0-194f-4ed8-9ca2-75b9a0831cfb)

Решение команды `DeviAⁱnts` задачи объединения ответов в группы схожих по смыслу в рамках тематики опроса для Хакатона [Цифровой прорыв](https://hacks-ai.ru).

Обработка ответов реализована кластеризацией с помощью модели машинного обучения `Transformers`. Интерфейс решения представлен в виде удобного веб-приложения. Визуализация реализована наглядным Sunburst из `Plotly`.


## Стек решения:
`Python`, `Sentence-Transformers`, `Transformers`, `PyTorch`, `Plotly`, `FastAPI`.


## Файлы

[`cluqwa_main.ipynb`](cluqwa_main.ipynb) — предобработка ответов, кластеризация. Решение хостится на Colab через ngrok

[`training mpnet.ipynb`](training(nbsp)mpnet.ipynb) — обучение MPNet на labeled датасете
