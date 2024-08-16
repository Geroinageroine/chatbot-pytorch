# Создание чат-бот в рамках обучения
Baseline из руководства у [Matthew Inkawhich](https://github.com/MatthewInkawhich)

## Задача

Здесь рассмотрен забавный и интересный пример использования моделей повторяющейся последовательности-в-последовательность для получения простого чат-бота, используя сценарии фильмов из [Cornell Movie-Dialogs
Corpus](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html).

### **Формат входных данных**

Данные расположены [здесь](https://zissou.infosci.cornell.edu/convokit/datasets/movie-corpus/movie-corpus.zip).

[Cornell Movie-Dialogs
Corpus](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html)
представляет собой богатый набор данных диалогов персонажей фильмов:

-   220 579 диалогов между 10 292 парами персонажей фильмов
-   9035 персонажей из 617 фильмов
-   304 713 всего высказываний

### Решение
В последнее время бум глубокого обучения позволил создать мощные генеративные модели, такие как Google [Neural
Conversational Model](https://arxiv.org/abs/1506.05869), что знаменует собой большой шаг к многодоменным генеративным разговорным моделям. В этом проекте мы реализуем основы построения генеративной модели чат-бота в PyTorch.

