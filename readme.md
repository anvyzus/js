# Homework


## Task 01.

Создайте переменную ```developer```, и присвойте ей "Ваше имя".

Создайте переменную ```name```, и присвойте ей значение переменной ```developer```.

Вывидете переменню ```name``` в консоль.


## Task 02.

Создайте страницу, которая спрашивает имя у пользователя и выводит его.


## Task 03.

Используя конструкцию ```if..else```, напишите код, который будет спрашивать: 'Какой сейчас год?'.

Если посетитель вводит '2020', то выводить 'Вы правы!', если что-то другое — выводить 'С луны свалися? 2020!'.


## Task 04.

Используя конструкцию ```if..else```, напишите код, который будет спрашивать: 'Введите любое целое число?'. Затем выведите alert:

```1```, если значение больше нуля,

```-1```, если значение меньше нуля,

```0```, если значение равно нулю.

## Task 05.

Напишите код, который будет запрашивать логин пользователя (```prompt```).

Если посетитель вводит 'admin', то спрашивать пароль, если нажал отмена (```escape```) — выводить 'Canceled', если вводит что-то другое — 'Access denied'.

Пароль проверять так. Если введён пароль 'passw0rd', то выводить 'Welcome home!', иначе — 'Wrong password', при отмене — 'Canceled'.


## Task 06.

Перепишите ```if``` с использованием оператора ```'?'```:

```js
let a = 1;
let b = 2;

if (a + b >= 3) {
    result = 'Yep!';
} else {
    result = 'Noup!';
}
```


## Task 07.

Перепишите ```if..else``` с использованием нескольких операторов ```'?'```:

```js
let name = 'admin';
let text;

if (name == 'admin') {
    text = 'Hi';
} else if (name == 'manager') {
    text = 'Hello';
} else if (name == '') {
    text = 'No login';
} else {
    text = '';
}
```

## Task 08.

We need a function that can transform a number into a string.

What ways of achieving this do you know?

Examples:

```js
numberToString(123); // returns '123';  
numberToString(999); // returns '999';
```


## Task 09.

We need a function that can transform a string into a number. What ways of achieving this do you know?

Note: Don't worry, all inputs will be strings, and every string is a perfectly valid representation of an integral number.

Examples:

```js
stringToNumber("1234") == 1234;
stringToNumber("605" ) == 605;
stringToNumber("1405") == 1405;
stringToNumber("-7"  ) == -7;
```


## Task 10.

Напишите цикл, который предлагает prompt ввести число, большее ```100```. Если посетитель ввел другое число — попросить ввести еще раз, и так далее.

Цикл должен спрашивать число пока либо посетитель не введет число, большее ```100```, либо не нажмет кнопку ```Cancel (ESC)```.

Предполагается, что посетитель вводит только числа, предусматривать обработку нечисловых строк в этой задаче необязательно.


## Task 11.

Натуральное число, большее ```1```, называется простым, если оно ни на что не делится, кроме себя и ```1```.

Другими словами, ```n > 1``` – простое, если при делении на любое число от ```2``` до ```n-1``` есть остаток.

Создайте код, который выводит все простые числа из интервала от ```2``` до ```10```. Результат должен быть: ```2, 3, 5, 7```.


P.S. Код также должен легко модифицироваться для любых других интервалов.

## Task 12.

Напишите программу, которая выводит через ```console.log``` все числа от ```1``` до ```100```, с двумя исключениями. Для чисел, нацело делящихся на ```3```, она должна выводить ```'Fizz'```, а для чисел, делящихся на ```5``` (но не на ```3```) – ```'Buzz'```.


## Task 13.

Исправьте предыдущую задачу ```FizzBuzz``` так, чтобы она выводила ```'FizzBuzz'``` для всех чисел, которые делятся и на ```3```, и на ```5```.


## Task 14.

Напишите программу, создающую строку, содержащую решётку ```8х8```, в которой линии разделяются символами новой строки. На каждой позиции либо пробел, либо ```\#```. В результате должна получиться шахматная доска.

```
# # # #
 # # # #
# # # #
 # # # #
# # # #
 # # # #
# # # #
 # # # #
```
Когда справитесь, сделайте размер доски переменным, чтобы можно было создавать доски любого размера.


## Task 15.

Напишите функцию pow(x,n), которая возвращает x в степени n. Иначе говоря, умножает x на себя n раз и возвращает результат.

```js
pow(3, 2) = 3 * 3 = 9
pow(1, 100) = 1 * 1 * ...* 1 = 1
```


## Task 16.

Create a function (or write a script in Shell) that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers.


## Task 17.

Jenny has written a function that returns a greeting for a user. However, she's in love with Johnny, and would like to greet him slightly different. She added a special case to her function, but she made a mistake.

Can you help her?

## Task 18.

In this simple assignment you are given a number and have to make it negative. But maybe the number is already negative?

Example:

```js
makeNegative(1); // return -1
makeNegative(-5); // return -5
makeNegative(0); // return 0
makeNegative(0.12); // return -0.12
```

Notes:

The number can be negative already, in which case no change is required.

Zero (0) is not checked for any specific sign. Negative zeros make no mathematical sense.


## Task 19.

Timmy & Sarah think they are in love, but around where they live, they will only know once they pick a flower each. If one of the flowers has an even number of petals and the other has an odd number of petals it means they are in love.

Write a function that will take the number of petals of each flower and return true if they are in love and false if they aren't.


## Task 20.

Complete the method that takes a boolean value and return a "Yes" string for true, or a "No" string for false.


## Task 21.

Последовательность чисел Фибоначчи вычисляется по формуле формулу ```F(n) = F(n-1) + F(n-2)```. В ней каждое следующее число вычисляется как сумма двух предыдущих. Первые два числа равны ```1``` и ```1```.

Напишите функцию ```fib(n)```, которая возвращает ```n```-е число Фибоначчи.

Например:

```js
console.log(fib(3)); //2
console.log(fib(7)); //13
console.log(fib(77)); //5527939700884757
```


## Task 22.

Напишите функцию ```checkSpam``` которая проверяет строку на содержание слов: ```spam```, ```sex```.

```js
checkSpam('get new Sex videos'); // true
checkSpam('[SPAM] How to earn fast money?'); // true
checkSpam('New PSD template'); // false
```


## Task 23.

Напишите функцию, которая принимает на вход строку и возвращает ее неизменной если ее длина не превышает ```20``` символов. Если длинна больше ```20```, то обрезает строку и добавляет в конец строки ```'...'```


## Task 24.

Given an input ```n```, write a function ```always``` that returns a function which returns ```n```. Ruby should return a lambda or a proc.

```js
var three = always(3);
three(); // returns 3
```


## Task 25.

Напиште код который выведет сотрудника который выполнил больше всех задач.

Например:

```js
let tasksCompleted = {
  'Anna': 29,
  'Nick': 35,
  'Elena': 1,
  'Viki': 99
};
```


## Task 26.

Напишите функцию ```multiplyNumeric``` которая принимает на вход объект и возвращает объект в котором все числовые значения у свойств умножены на ```2```.

```js
// Before
var image = {
    width: 100,
    height: 400,
    title: 'Cool image'
};

multiplyNumeric(image);

// after
image = {
    width: 200,
    height: 800,
    title: 'Cool image'
};
```


## Task 27.

Напишите код, который:

1. Запрашивает по очереди значения при помощи ```prompt``` и сохраняет их в массиве.

2. Заканчивает ввод, как только посетитель введёт пустую строку, не число или нажмёт ```"Отмена"```.

3. При этом ноль ```0``` не должен заканчивать ввод, это разрешённое число.

4. Выводит сумму всех значений массива когда ввод прекращен.

## Task 28.

У объекта есть свойство ```className```, которое хранит список ```css-класов``` – слов, разделенных пробелами:

```js
var obj = {
  className: 'open menu'
};
```

Напишите функцию ```removeClass(obj, cls)```, которая удаляет класс ```cls```, если он есть:

```js
removeClass(obj, 'open'); // obj.className='menu'
removeClass(obj, 'blabla'); // без изменений
```

P.S. Дополнительное усложнение. Функция должна корректно обрабатывать дублирование класса в строке:

```js
obj = {
  className: 'my menu menu'
};

removeClass(obj, 'menu');

console.log( obj.className ); // 'my'
```

Лишних пробелов после функции образовываться не должно.


## Task 29.

Есть массив строк ```arr```. Создайте массив ```arrSorted``` — из тех же элементов, но отсортированный.

Исходный массив не должен меняться.

```js
var arr = ['HTML', 'JavaScript', 'CSS'];

// ... ваш код ...

console.log( arrSorted ); // CSS, HTML, JavaScript
console.log( arr ); // HTML, JavaScript, CSS (без изменений)
```

## Task 30.

Необходимо отсортировать массив в случайном порядке используя метод ```sort```.

```js
var arr = [1, 2, 3, 4, 5];

arr.sort(ваша функция);

console.log( arr ); // элементы в случайном порядке, например [3,5,1,2,4]
```

## Task 31.

Напишите код, который отсортирует массив объектов ```people``` по полю ```age```.

Например:

```js
var vasya = { name: 'Вася', age: 23 };
var masha = { name: 'Маша', age: 18 };
var vovochka = { name: 'Вовочка', age: 6 };

var people = [vasya, masha, vovochka];

... ваш код ...

// теперь people: [vovochka, masha, vasya]
console.log(people[0].age) // 6
```

Выведите список имён в массиве после сортировки.

## Task 32.

Палиндром - это строка которая читается с обоих сторон одинаково. Например: Анна, оно, А роза упала на лапу Азора.

Необходимо написать функцию ```isPal(string)``` которая возвращает ```true``` или ```false``` в зависимости от того является ли строка палиндромом или нет.

```js
console.log( isPal('Anna') ); // true
console.log( isPal('А роза упала на лапу Азора') ); //true
console.log( isPal('Вася') ); //false
console.log( isPal('12321') ); //true
console.log( isPal('123212') ); //false
```

# Task 33.

Напишите функцию ```unique(arr)```, которая возвращает массив, содержащий только уникальные элементы ```arr``` (```arr``` — массив строк).

```js
var strings = ['кришна', 'кришна', 'харе', 'харе', 'харе', 'харе', 'кришна', 'кришна', '8-()'];

console.log( unique(strings) ); // кришна, харе, 8-()
```


# Task 34.

Анаграммы — слова, состоящие из одинакового количества одинаковых букв, но в разном порядке. Например:

воз - зов; киборг - гробик; корсет - костер - сектор. 

Напишите функцию ```anClean(arr)```, которая возвращает массив слов, очищенный от анаграмм.

```js
var arr = ['воз', 'киборг', 'корсет', 'ЗОВ', 'гробик', 'костер', 'сектор'];

console.log( anClean(arr) ); // 'воз,киборг,корсет' или 'ЗОВ,гробик,сектор'
```

Из каждой группы анаграмм должно остаться только одно слово, не важно какое.


# Task 35.

Fellow code warrior, we need your help! We seem to have lost one of our array elements, and we need your help to retrieve it! Our array, ```superImportantArray```, was supposed to contain all of the integers from ```0``` to ```9``` (in no particular order), but one of them seems to be missing.

Write a function called ```getMissingElement``` that accepts an array of unique integers between ```0``` and ```9``` (inclusive), and returns the missing element.

Examples:

```js
getMissingElement( [0, 5, 1, 3, 2, 9, 7, 6, 4] ) // returns 8
getMissingElement( [9, 2, 4, 5, 7, 0, 8, 6, 1] ) // returns 3
```


# Task 36.

Your task is to add a new property ```usersAnswer``` to every object in the array ```questions```. The value of ```usersAnswer``` should be set to ```null```. The solution should work for array of any length.

For example:

```js
var questions = [{
    question: "What's the currency of the USA?",
    choices: ["US dollar", "Ruble", "Horses", "Gold"],
    corAnswer: 0
}, {
    question: "Where was the American Declaration of Independence signed?",
    choices: ["Philadelphia", "At the bottom", "Frankie's Pub", "China"],
    corAnswer: 0
}];

After adding the property the result should be:

var questions = [{
    question: "What's the currency of the USA?",
    choices: ["US dollar", "Ruble", "Horses", "Gold"],
    corAnswer: 0,
    usersAnswer: null
}, {
    question: "Where was the American Declaration of Independence signed?",
    choices: ["Philadelphia", "At the bottom", "Frankie's pub", "China"],
    corAnswer: 0,
    usersAnswer: null
}];
```

The ```questions``` array is already defined for you and is not the same as the one in the example.


## Task 37.

Create a function, ```getVillainName```, that returns a villain name based on the user's birthday. (The birthday will be passed to the function as a valid Date object, so for simplicity, there's no need to worry about converting strings to dates.)

The first name will come from the month, and the last name will come from the last digit of the date.

Month -> first name

    January -> "The Evil"
    February -> "The Vile"
    March -> "The Cruel"
    April -> "The Trashy"
    May -> "The Despicable"
    June -> "The Embarrassing"
    July -> "The Disreputable"
    August -> "The Atrocious"
    September -> "The Twirling"
    October -> "The Orange"
    November -> "The Terrifying"
    December -> "The Awkward"

Last digit of date -> last name

    0 -> "Mustache"
    1 -> "Pickle"
    2 -> "Hood Ornament"
    3 -> "Raisin"
    4 -> "Recycling Bin"
    5 -> "Potato"
    6 -> "Tomato"
    7 -> "House Cat"
    8 -> "Teaspoon"
    9 -> "Laundry Basket"

The returned value should be a string in the form of "First Name Last Name".

For example, a birthday of November 18 would return "The Terrifying Teaspoon".


# Task 38.

Make the ```sum()``` function return the sum of the values in the passed in array. Your solution must use the ```reduce()``` function of the built-in javascript ```Array``` object. If you're not familiar with ```reduce()```, reading over the documentation may help.

```js
function sum(array) {
  // Use array.reduce() to find and return the
  // sum of the values in array.
}
```

For example:

```js
var someNumbers = [1,2,3,4,5,6,7,8,9,10];

sum(someNumbers); // should return 55
```


## Task 39.

You live in the city of Cartesia where all roads are laid out in a perfect grid. You arrived ten minutes too early to an appointment, so you decided to take the opportunity to go for a short walk. The city provides its citizens with a Walk Generating App on their phones -- everytime you press the button it sends you an array of one-letter strings representing directions to walk (eg. ['n', 's', 'w', 'e']). You always walk only a single block in a direction and you know it takes you one minute to traverse one city block, so create a function that will return true if the walk the app gives you will take you exactly ten minutes (you don't want to be early or late!) and will, of course, return you to your starting point. Return false otherwise.

Note: you will always receive a valid array containing a random assortment of direction letters ('n', 's', 'e', or 'w' only). It will never give you an empty array (that's not a walk, that's standing still!).


## Task 40.

We want to create a function, which returns an array of functions, which return their index in the array. For better understanding, here an example:

```js
var callbacks = createFunctions(5); // create an array, containing 5 functions

callbacks[0](); // must return 0
callbacks[3](); // must return 3
```

We already implemented that function, but when we actually run the code, the result doesn't look like what we expected. Can you spot, what's wrong with it? A test fixture is also available


## Task 41.

There's no such thing as private properties on a coffeescript object! But, maybe there are?

Implement a function ```createSecretHolder(secret)``` which accepts any value as secret and returns an object with ONLY two methods

```js
getSecret() which returns the secret
setSecret() which sets the secret

obj = createSecretHolder(5)
obj.getSecret() # returns 5
obj.setSecret(2)
obj.getSecret() # returns 2
```


## Task 42.

Deferring a function execution can sometimes save a lot of execution time in our programs by postponing the execution to the latest possible instant of time, when we're sure that the time spent while executing it is worth it.

Write a method ```make_lazy``` that takes in a function (symbol for Ruby) and the arguments to the function and returns another function (lambda for Ruby) which when invoked, returns the result of the original function invoked with the supplied arguments.

For example:

Given a function ```add```

```js
function add (a, b) {
  return a + b;
}
```

One could make it ```lazy``` as:

```js
var lazy_value = make_lazy(add, 2, 3);
```

The expression does not get evaluated at the moment, but only when you invoke ```lazy_value``` as:

```js
lazy_value() => 5
```

The above invokation then performs the sum.

Please note: The functions that are passed to ```make_lazy``` may take one or more arguments and the number of arguments is not fixed.


# Task 43.

Есть объект ```ladder```

```js
var ladder = {
  step: 0,
  up: function() { // вверх по лестнице
    this.step++;
  },
  down: function() { // вниз по лестнице
    this.step--;
  },
  showStep: function() { // вывести текущую ступеньку
    alert( this.step );
  }
};
```

Сейчас, для последовательного вызова нескольких методов объекта, нужно делать так сделать так:

```js
ladder.up();
ladder.up();
ladder.down();
ladder.showStep(); // 1
```

Модифицируйте код методов объекта, чтобы вызовы можно было делать цепочкой:

```js
ladder.up().up().down().up().down().showStep(); // 1

```
Такой подход называется «чейнинг» (chaining).


# Task 44.

Напишите конструктор ```Calculator```, который создаёт расширяемые объекты-калькуляторы.

Эта задача состоит из двух частей, которые можно решать одна за другой.

Первый шаг задачи: вызов ```calculate(str)``` принимает строку, например: ```1 + 2```, с жёстко заданным форматом ```ЧИСЛО операция ЧИСЛО``` (по одному пробелу вокруг операции), и возвращает результат. Понимает плюс ```+```и минус ```-```. Пример использования:

```js
var calc = new Calculator;

console.log( calc.calculate('3 + 7') ); // 10
```

Второй шаг — добавить калькулятору метод ```addMethod(name, func)```, который учит калькулятор новой операции. Он получает имя операции ```name``` и функцию от двух аргументов ```func(a, b)```, которая должна её реализовывать. Например, добавим операции умножить , поделить ```/``` и возвести в степень ```**```:

```js
var powerCalc = new Calculator;
powerCalc.addMethod('*', function(a, b) {
  return a * b;
});
powerCalc.addMethod('/', function(a, b) {
  return a / b;
});
powerCalc.addMethod('**', function(a, b) {
  return Math.pow(a, b);
});

let result = powerCalc.calculate('2 ** 3');
console.log( result ); // 8
```

Поддержка скобок и сложных математических выражений в этой задаче не требуется.

Числа и операции могут состоять из нескольких символов. Между ними ровно один пробел.

Предусмотрите обработку ошибок. Какая она должна быть – решите сами.
