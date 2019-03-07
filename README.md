# JavaCore_Lesson-12
Collection Framework: List, ArrayList, LinkedList

* [Завдання 1](https://github.com/AlexeyDolgov/JavaCore_Lesson-12/tree/master/JavaCore_Lesson-12/src/ua/lviv/lgs/task12_1)<br>
(переписати завдання до [уроку 8](https://github.com/AlexeyDolgov/JavaCore_Lesson-08/tree/master/JavaCore_Lesson-08/src/ua/lviv/lgs/task8_1),
де ми створювали консольну програму для роботи з Enum, замінивши всі контейнери на ArrayList; протестувати програму, щоб вона успішно
з ним працювала)<br><br>
Написати консольну програму для роботи з Enum.<br><br>
Створити enum <i>Сезони</i>, в якому оголосити такі константи: Зима, Весна, Літо, Осінь.<br><br>
Створити enum <i>Місяці</i>, в якому створити 12 констант-місяців року. Оголосити змінну дні та змінну сезон типу Сезон як поле
enum. Створити конструктор з визначеними параметрами в enum Місяці, в який як параметри передати змінну дні та сезон. Описати getters
до даних полів (дні, сезони).<br><br>
Створити консольне меню, в якому реалізувати наступні пункти:<br>
• перевірити, чи є такий місяць (місяць вводимо з консолі) (передбачити, щоб регістр букв був не важливим)<br>
• вивести всі місяці з такою ж порою року<br>
• вивести всі місяці, які мають таку саму кількість днів<br>
• вивести на екран всі місяці, які мають меншу кількість днів<br>
• вивести на екран всі місяці, які мають більшу кількість днів<br>
• вивести на екран наступну пору року<br>
• вивести на екран попередню пору року<br>
• вивести на екран всі місяці, які мають парну кількість днів<br>
• вивести на екран всі місяці, які мають непарну кількість днів<br>
• вивести на екран, чи введений з консолі місяць має парну кількість днів<br><br>

* [Завдання 2](https://github.com/AlexeyDolgov/JavaCore_Lesson-12/tree/master/JavaCore_Lesson-12/src/ua/lviv/lgs/task12_2)<br>
(переписати завдання до [уроку 11](https://github.com/AlexeyDolgov/JavaCore_Lesson-11/tree/master/JavaCore_Lesson-11/src/ua/lviv/lgs/task11_2),
де ми створювали машину, замінивши всі контейнери на ArrayList; протестувати програму, щоб вона успішно з ним працювала)<br><br>
Створити сутності <i>Авто</i>, <i>Кермо</i>, <i>Двигун</i>.<br><br>
<i>Авто</i> володіє полями кількість кінських сил, рік випуску.<br><br>
<i>Кермо</i> володіє полями діаметр колеса, матеріал, з якого зроблено кермо (шкіра, алькантара).<br><br>
<i>Двигун</i> володіє полем кількість циліндрів.<br><br>
Створити <i>List</i> та наповнити його об’єктами класу Авто. Всі значення конструктора заповнюються рандомно.<br><br>
Створити консольне меню, яке буде мати наступні елементи:<br>
• вивести лист об’єктів класу Авто на консоль<br>
• для всіх об’єктів листа засетати однаковий об’єкт класу Авто та вивести лист на консоль<br><br>

* [Завдання 3](https://github.com/AlexeyDolgov/JavaCore_Lesson-12/tree/master/JavaCore_Lesson-12/src/ua/lviv/lgs/task12_3)<br>
Вивчивши будову ArrayList створити свій власний <i>ArrayList</i>, який буде динамічно розширятись і мати лише два методи:<br>
• add() додати в кінець списку<br>
• remove(index) видалити за індексом<br><br>
Створити <i>main</i> метод, де заповнити даними власний ArrayList, використовуючи метод add(), і протестувати його метод видалення
remove(index).<br><br>
