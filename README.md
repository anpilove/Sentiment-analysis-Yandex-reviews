<a id='ENG'></a>
<a href="#RUS"><img src='https://img.shields.io/badge/ENG -Go to RUS description-blue'></a>

# Sentiment analysis Yandex reviews

In this project, I've worked with the Yandex reviews dataset, conducted analytics, and tested various models.

| Model                  | precision | recall | f1-score |
| ---------------------- | --------- | ------ | -------- |
| MultinomialNB          | 0.64      | 0.71   | 0.67     |
| LogisticRegression     | 0.84      | 0.73   | 0.77     |
| RandomForestClassifier | 0.81      | 0.73   | 0.73     |
| CatBoostClassifier     | 0.83      | 0.72   | 0.76     |
| LGBMClassifier         | 0.82      | 0.68   | 0.73     |
| XGBClassifier          | 0.77      | 0.53   | 0.61     |
| RNN                    | 0.82      | 0.73   | 0.77     |
| LSTM                   | 0.84      | 0.74   | 0.78     |

In the future, I plan to create an interactive map displaying the reviews.

---

## Project Organization

    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks.
    │
    └──requirements.txt    <- The requirements file for reproducing the analysis environment, e.g.
                             generated with `pip freeze > requirements.txt`

---

<a id='RUS'></a>
<a href="#ENG"><img src='https://img.shields.io/badge/RUS -Go to ENG description-blue'></a>

# Sentiment analysis Yandex reviews

В этом проекте я провел анализ датасета отзывов Яндекса и протестировал множество моделей.

В будущем планирую создать интерактивную карту, на которой будут отображены отзывы.

---

## Организация проекта

    ├── README.md          <- Основной README для разработчиков, использующих этот проект.
    │
    ├── models             <- Обученные модели.
    │
    ├── notebooks          <- Jupyter ноутбуки.
    │
    └── requirements.txt   <- Файл с требованиями для воспроизведения окружения анализа, например
                              созданный с помощью `pip freeze > requirements.txt`.
