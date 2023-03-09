# F. Пути в дереве

Дано укоренённое дерево на N вершинах и число X. 
В каждой вершине записано число — её вес.

Назовём восходящим путь a<sub>i</sub>, p (a<sub>i</sub>), p(p(a<sub>i</sub>)), ..., где p(a) — родитель вершины a. 
Проще говоря, восходящий путь — это путь, который начинается с некоторой вершины и двигается в сторону корня (не обязательно доходя до него). Путь может состоять из одной вершины.
Весом пути назовём суммарный вес вершин на этом пути.
Найдите количество восходящих путей с весом
X
.


## Формат ввода
В первой строке дано число вершин n (1 ≤ n ≤ 2⋅10<sup>5</sup>) и число X (−10<sup>9</sup> ≤ X ≤ 10<sup>9</sup>).

В следующих n строках по одной в строке заданы вершины. i -я вершина задаётся двумя числами — p<sub>i</sub> и w<sub>i</sub>, записанными через пробел. p<sub>i</sub> — это либо номер вершины-родителя вершины i, 
в этом случае 0 ≤ p<sub>i</sub> ≤ n−1, либо −1, если вершина i является корнем. 

wi — это вес вершины i (−10<sup>4</sup> ≤ w<sub>i</sub> ≤ 10<sup>4</sup>).

## Формат вывода

Выведите одно целое число — количество восходящих путей веса X.

### Пример 1

<table><tr>
<td>
6 3<br>
-1 1<br>
0 1<br>
0 1<br>
1 1<br>
2 2<br>
3 1
</td>
<td>
3<br>
<br>
<br>
<br>
<br>
<br>
<br>
</td>
</tr></table>

### Пример 2

<table><tr>
<td>
1 2<br>
-1 1
</td>
<td>
0<br>
<br>
</td>
</tr></table>