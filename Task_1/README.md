## Task_1

### Опис

>Об'єкт ladder призначений для симуляції підняття та спуску по сходах. Він зберігає поточний крок і надає методи для переміщення вгору або вниз, а також для показу поточного кроку.

### Використання
>Ви можете взаємодіяти з об'єктом ladder, використовуючи його методи:

>
> >up: Піднімає вас на один крок.
>
> >down: Опускає вас на один крок.
>
> >showStep: Показує поточний крок.

### Ось як ви можете використовувати об'єкт ladder:

```javascript
ladder.up().up().down().showStep(); // Результат: 1
```

>Цей фрагмент коду демонструє ланцюжок викликів методів, що дозволяє виконати декілька дій послідовно на об'єкті ladder.