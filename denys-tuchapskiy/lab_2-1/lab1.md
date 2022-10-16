Львівський національний університет природокористування

Факультет механіки, енергетики та інформаційних технологій

Кафедра інформаційних технологій

Звіт з лабораторної роботи №1
на тему: 

# Твірні шаблони. Шаблон прототип.

Виконав: ст. групи ІТ-22сп Тучапський Д. Ю.

Перевірив: Татомир А. В.

**Мета роботи:** ознайомитися з твірними шаблонами.

## Завдання
1. Ознайомитися з твірними шаблонами.
2. Написати базову програму згідно виданого завдання та проаналізувати її роботу.

## Хід роботи
1. Я ознайомився з твірними шаблонами. Вони відповідають за зручне та безпечне створення нових об'єктів або навіть цілих сімейств об'єктів. Патерн Прототип доручає процес копіювання самим об’єктам, які треба скопіювати.
Реалізація копіювання відбувається за допомогою метода clone зазвичай.
Метод створює новий об’єкт поточного класу й копіює в нього значення всіх полів власного об’єкта. 
Таким чином можна скопіювати навіть приватні поля, оскільки більшість мов програмування дозволяє 
отримати доступ до приватних полів будь-якого об’єкта поточного класу.
2. [Код програми.](./lab_1.py)  
![Результат виконання програми.](result-of-task.PNG)

**Висновок:** У ході лабораторної роботи №1, я ознайомився з твірними шаблонами, ці шаблони дозволяють зручно та безпечно створювати нові об'єкти, ознайомився з шаблоном прототип, за його допомогою об'єкти самі себе копіюють, створюючи новий об'єкт зі всіма полями. Написав програму, в якій на прикладі об'єкта Jhon, за допомогою метода deepcopy створився об'єкт Jane. Отже, я зрозумів як використовувати на практиці шаблон прототип.