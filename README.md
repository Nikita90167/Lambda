# Лямбда-выражения

![](https://img.shields.io/github/languages/count/Nikita90167/Lambda) ![](https://img.shields.io/github/languages/top/Nikita90167/Lambda) ![](https://img.shields.io/github/repo-size/Nikita90167/Lambda)

## Введение в курс дела

> Лямбда-выражения - это упрощённая запись анонимного класса, реализующего функциональный интерфейс.

Для того, чтобы понять, насколько это упрощенная запись я продемонстрирую на примере.

***Отличия:***

Анонимный класс:

```java
Collections.sort(ls, new Comparator(){
      public int compare(Object o1, Object o2)
       {
          return 0;
       }
 }
```

* Такая реализация нужна в тех, случаях если экземпляр объекта необходим нам 1 раз.

Лямбда-выражения:

```java
Comparator<Person> comparatorLambda;
        comparatorLambda = (Object1, Object2) -> return 0;
```

* По сути это та же самая логика, но ее реализация сокращена до 2 строк. Это делает код более компактным и читабельным.

> *Подробнее ознакомиться с лямбда-выражением вы можете по [ссылке](https://metanit.com/java/tutorial/9.1.php)*

***Вывод:*** лучше использовать лямбда-выражения, а не ~~анонимный класс~~.

## Описание проекта

В этом проекте я интегрировал механизм лямбда-выражения в свою работу для [решения поставленной задачи](https://github.com/lordpank/Lambda)
