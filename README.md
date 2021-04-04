# MyElasticLogisticRegression

Здесь вы можете увидеть мою реализацию ***Логистической Регрессии***, известного алгоритма машинного обучения, используемого в задачах классиификации. Данная реализация содержит в себе *L1* и *L2* регуляризации (**elastic net**), т.е. способы борьбы с переобучением и большими весами модели.

#### Особенности реализации:
- Имеет схожий интерфейс с классом [*LogisticRegression*](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html) библиотеки [*scikit-learn*](https://scikit-learn.org/)
- Использует оптимизацию **Batch Gradient Descent**, давая возможность подбирать размер батча пользователю
- Обучение делится на эпохи, и в течении каждой эпохи алгоритм обучается на каждом из наблюдений ровно один раз. Количество эпох также задается пользователем
- Возможность получить веса обученной модели, методом `get_weights()`

Пример использования можно увидеть в этом [jupyter ноутбуке](https://github.com/hzchet/MyElasticLogisticRegression/blob/main/Usage%20Example.ipynb), в котором также можно будет найти визуализации илюстрирующие классификацию нашей модели.
