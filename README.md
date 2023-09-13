# Classification-of-Russian-language-sports-texts

## Классификация русскоязычных спортивных текстов

Решена задача классификации русскоязычных спортивных текстов из социальных сетей.

- выполнена очистка и лемматизация 38740 постов, в которых упоминается один из 13 видов спорта;

- протестированы различные модели векторного пространства и алгоритмы машинного обучения для классификации текстов;

- использована стек-модель для увеличения качества классификации ($F1$ = 0,872);

- с помощью нейронной сети со слоем EmbeddingBag, реализованной с использованием библиотеки PyTorch, получено значение целевой метрики качества классификации $F1$ = 0,887.

Фрагменты кода:
- [классификации с использованием слоя Transformer (Keras)](https://github.com/constdivis/constdivis/blob/main/text-classification-with-transformer-82-accur.ipynb)
[![](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/constantinedivis/text-classification-with-transformer-82-accur)

- [предобработка данных и классификация с EmbeddingBag (PyTorch)](https://github.com/constdivis/Classification-of-Russian-language-sports-texts/blob/918c0d19f1c11e41349ee3246ce9c8ca8ccea8b6/text-classification-with-embeddingbag-88-accur.ipynb)
[![](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/constantinedivis/text-classification-with-embeddingbag-88-accur)
