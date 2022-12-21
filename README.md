## Сравнение аналогов
## Принцип отбора аналогов
    Целью данной работы является исследование алгоритма искуственной пчелиной колонии, его сравнение по качеству и времени решения с другими существующими алгоритмами покрытия множества. Для поиска аналогов использовались поисковые системы Google и Yandex, а также научные поисковые системы Web of Science и электронная библиотека eLIBRARY.RU. В качестве ключевых слов были использованы следующие: "решение задачи покрытия множества", "эвристические алгоритмы", "решение NP-полной задачи", "стохастические бионические алгоритмы". 
    В качестве аналогов были отобраны алгоритмы, наиболее похожие на алгоритм искуственной пчелиной колонии по категории и целям, для которых они применяются. 

### Greedy algorithm
    Зачастую для решения задачи покрытия множества используется жадный алгоритмх[1]. Это априорный алгоритм с приближённой оценкой, который можно исследовать по качеству и времени решения. Однако, он не соответсвует проблеме данной работы, в которой будет произведено сравнение эвристических алгоритмов. Его плюс в том, что из-за своей популярности он имеет множество готовых реализаций, в том числе и для задачи покртыиия множества.

### Genetic algorithm
    Данный алгоритм является одним из основных подходов к решению задачи покрытия множества[2]. Это эвристический алгоритм, так как в нём покрытия начальной популяции строятся случайным образом[3].

### Cat swarm optimization algorithm
    Алгоритм стаи кошек успешно применяется в различных оптимизационных областях науки[4]. Он является эвристическим, поэтому его также можно использовать для решения задачи покрытия множествах[5]. Данный алгоритм так же, как и алгоритм искуственной пчелиной колонии, относится к алгоритмам роевого интеллекта. Особи стаи взаимодействуют по определённым правилам, которые делают деятельность стаи более эффективной. 

### Ant colony optimization algorithm
    Муравьиный алгоритм используется для поиска сложных решений оптимизационных задач[7]. Прежде всего, он был использован для решении задачи коммивояжера, однако он применим и к задаче покрытия множества, так как является эвристистическим. Его устройство схоже с алгоритмом искуственной пчелиной колонии. Наилучшие результаты алгоритм показывает при решении задач с большими размерностями областей поиска. Алгоритм имеетт различные модификации. В данной работе за основу будет принята его классическая версия[8]. 

### Cuckoo search algotithm
    Алгоритм поиска кукушки также является одним из примеров алгоритма роевого интеллекта[8]. Для сравнения в данной работе может быть использована его модифицированная версия[9]. Это эвристический оптимизационный алгоритм, который имеет в свододном доступе уже готовые реализации на языке Python.


## Критерии сравнения аналогов

### Ориентированность на задачу покрытия множества
    В рамках данной работы будет исследовано влияние параметров метаэвристики на качество и время решения. Для этого необходимо иметь код алгоритма, уже адапртированный для решения задачи покрытия множества (адаптация кода алгоритма искуственной пчелиной колонии входит в задачи работы).

### Является эвристическим алгоритмом
    NP-полная задача имеет высокую вычислительную сложность, поэтому для её решения следует использовать эвристический алгоритм. Иначе поиск решения может занять слишком продожительное количесвто времени.

### Имеется реализиция на языке программирования Python
    Результатом выполнения работы должен быть отлаженный код на языке программирования Python, реализующий выбранную метаэвристику. Приложение, которое будет использовано для проведения экспериментов, работает только с хранимыми процедурами Microsoft SQL Server, поэтому будет полезно иметь уже готовые решения.   

## Таблица сравнения по критериям

| Критерий/аналог       |   Greedy     | Genetic  | Cat swarm optimization  | Ant colony optimization | Cuckoo search |
| ------------- |:------------------:| :--------------:|:---------: |:-----------: |:----------: |
| Задача покртытия множества     | + | + | - | - | - |
| Эвристический алгоритм         | - | + | + | + | + |
| Реализация на Python           | + | + | - | + | + |

## Выводы по итогам сравнения 
    По итогам сравнения аналогов, можно сделать вывод о том, что существует достаточно много алгоритмов для решения задачи покрытия множества. Они могут отличаться по принципу работы, области применению, а также по распространённости и популярности. Были отобраны те алгоритмы, которые наиболее похожи на алгоритм искуственной пчелиной колонии и обладают схожими параметрами. 

## Источники
1. [Greedy algorithm]
2. [Genetic algorithm](https://habr.com/ru/post/498308) 
3. Нгуен Минь Ханг ПРИМЕНЕНИЕ ГЕНЕТИЧЕСКОГО АЛГОРИТМА ДЛЯ
ЗАДАЧИ НАХОЖДЕНИЯ ПОКРЫТИЯ МНОЖЕСТВА
4. [CSO](https://habr.com/ru/post/328760/)
5. S. C. Chu and P. W. Tsai, “Computational intelligence based on the behavior of cats,” International Journal of Innovative Computing, Information and Control, vol. 3, no. 1, pp. 163–173, 2007. 
6. [ACO](http://www.scholarpedia.org/article/Ant_colony_optimization)
7. M. Dorigo, L. M. Gambardella, Ant Colony System: A Cooperative Learning Approach to the Traveling Salesman Problem // IEEE Transactions on Evolutionary Computation Vol. 1, 1, стр. 53-66, 1997 г.
8. [Cuckoo_search](https://en.wikipedia.org/wiki/Cuckoo_search)
9. X.-S. Yang; S. Deb (December 2009). Cuckoo search via Lévy flights. World Congress on Nature & Biologically Inspired Computing (NaBIC 2009). IEEE Publications. pp. 210–214.
