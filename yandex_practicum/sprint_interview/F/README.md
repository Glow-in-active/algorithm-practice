# E. Хорошие строки

Назовем строку хорошей, если в ней нет двух соседних букв, которые различаются только регистром. Например, строка «abba» хорошая, а строка «aBba» нет.
Со строкой можно делать преобразование: если два соседних символа обозначают одну и ту же букву, но записаны в разных регистрах, то их можно удалить. При этом строка «схлопнется», то есть пробелов при удалении не образуется.

Цепочкой таких преобразований можно превратить любую строку в хорошую.

По заданной строке найдите хорошую строку, в которую ее можно превратить.

## Формат ввода

На вход подаётся строка, состоящая из больших и маленьких латинских букв. Длина строки не превосходит 10<sup>5</sup>.

## Формат вывода

Выведите хорошую строку, в которую можно превратить данную.

### Пример 1

<table><tr>
<td>
vxOoOoVvx
</td>
<td>
vxx
</td>
</tr></table>

### Пример 2

<table><tr>
<td>
abBa
</td>
<td>
aa
</td>
</tr></table>

### Пример 3

<table><tr>
<td>
AbBa
</td>
<td>
 
</td>
</tr></table>

