![alt text](OIP.jpg)
# Что такое Object в JS ?
## Объект в JavaScript - это коллекция свойств, и каждое свойство состоит из имени (также известного как ключ) и значения. Значение свойства может быть любым типом данных JavaScript, включая функции, массивы и другие объекты.
...
```js
let person = {
    firstName : "Ismail",
    lastName : "Tashpulatov",
    age : 17
}
console.log(person)
```
...
# Методы в JS : 
## Object.entries() <br> Этот метод показывает нам ключи Обьекта в одельном массиве а заначение в другом массиве и все они в одном большом массиве !
```js
let obj = { name: "Ismail", age: 17,};
console.log(Object.entries(obj));
// Output: [ [ 'name', 'Ismail' ], [ 'age', 17] ]
```
...
## Object.keys() <br> Метод возвращает массив, содержащий имена всех перечисляемых свойств объекта. Эти свойства возвращаются в том порядке, в котором они были определены в объекте.
```js
let obj = { name: "Ismail", age: 17,};
console.log(Object.keys(obj));
// Output: [ 'name', 'age' ]
```
...
## Object.values() <br> Метод возвращает массив, содержащий значения всех перечисляемых свойств объекта. Эти значения возвращаются в том порядке, в котором они были определены в объекте.
```js
let obj = { name: "Ismail", age: 17,};
console.log(Object.values(obj));
// Output: [ 'Ismail', 17 ]
```
...
# Что такое Destructuring & Spread в JS ? 
## Destructuring - это синтаксис JavaScript, который позволяет извлекать значения из массивов или свойства из объектов и присваивать их новым переменным.
```js
let person = {
  name: "Ismail",
  age: 17
};

let { name, age } = person;

console.log(name); // Output: "Ismail"
console.log(age);  // Output: 17
```
...
## Spread - это оператор (...), который позволяет расширять элементы массива (в местах, где ожидается ноль или более аргументов или элементов) или расширять свойства объекта (в местах, где ожидаются ноль или более пар ключ-значение).
```js
let arr1 = [1, 2, 3];
let arr2 = [...arr1, 4, 5];

console.log(arr2); // Output: [1, 2, 3, 4, 5]
```