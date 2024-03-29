# Algorithms_on_graphs
Поиск пути, проходящего через все дуги орграфа, причем начальная и конечные вершины не должны быть смежными. Реализация графа: матрица смежности.

В программе есть два примера. В одном есть решение, во втором пути, удовлетворяющего заданию нет.

Файл main.py содержит инициализацию графа, а также вызов метода для поиска пути по заданию.

Файл graph.py содержит АТД "Граф", а также методы для работы с ним.

Пример 1 (есть путь, проходящий через все дуги, но начальная и конечная вершины смежные):

Рисунок графа:

![image](https://github.com/Sasha300578/Algorithms-_on_graphs/assets/113348429/84fd5d3d-4325-48dc-802f-8b40e5fabfde)

Матрица смежности:

![image](https://github.com/Sasha300578/Algorithms-_on_graphs/assets/113348429/878a7018-802e-42c5-93f3-784a21f87b20)

Обход графа (на рисунке указан один проход из вершины А):

![image](https://github.com/Sasha300578/Algorithms-_on_graphs/assets/113348429/12278f8c-e2f0-4a10-8916-34c5aa90cebd)

Аналогичный обход графа будет осуществлен из всех вершин. Если найдется путь, который проходит через все дуги орграфа, причём проходя через каждую дугу лишь один раз, а также начальная и конечная вершины не будут смежными, то выведется путь, проходящий через все дуги.

Вывод программы:
 
![image](https://github.com/Sasha300578/Algorithms-_on_graphs/assets/113348429/16a01a68-d529-4189-8a83-44067f82c57c)

Пример 2 (есть путь, проходящий через все дуги):

Рисунок графа:

![image](https://github.com/Sasha300578/Algorithms-_on_graphs/assets/113348429/17e158cb-54eb-4a87-94c0-41bb51ad65cf)

Матрица смежности:

![image](https://github.com/Sasha300578/Algorithms-_on_graphs/assets/113348429/30f08e8d-8743-4e47-b76f-ae26e9d73ab6)

Обход графа (на рисунке указан один проход из вершины А):


![image](https://github.com/Sasha300578/Algorithms-_on_graphs/assets/113348429/521e4cfd-70bc-4f80-8e7a-fe637c0aaed3)

Аналогичный обход графа будет осуществлен из всех вершин. Если найдется путь, который проходит через все дуги орграфа, причём проходя через каждую дугу лишь один раз, а также начальная и конечная вершины не будут смежными, то выведется путь, проходящий через все дуги.

Вывод программы:

![image](https://github.com/Sasha300578/Algorithms-_on_graphs/assets/113348429/2a7dc506-5058-4904-9fba-bdb2e8b9b78e)




