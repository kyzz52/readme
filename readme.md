# Программа поиска факториала на языке JavaScript
## 1. Задаем переменные
```
let factorial=5;
let n=1;
let count=1;
```
## 2. Делаем цикл используя оператор "for"
```
for (let i = 1; i <= factorial; i++) {
    n=n*i;
}
```
В этом цикле задаем переменную "i" и присваиваем значение "1", задаем условие чтобы "i" была меньше или ровно переменной "factorial", и задаем такое действие, которое будет выполняться пока условие соблюдается  `i++`

Еще одно действие которое не входит в описание цикла `n=n*i` 
## 3.Выводим в консоль
 `console.log(n)`