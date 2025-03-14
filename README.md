# Домашнее задание к лекции «Регулярные выражения»

[![Build status](https://ci.appveyor.com/api/projects/status/fld59xpcifx6oet0?svg=true)](https://ci.appveyor.com/project/Anton17848/regular-expressions)


**Важно**: каждая задача выполняется в виде отдельного проекта с собственным GitHub репозиторием.

**Важно**: код должен проходить ESLint без ошибок.

**Важно**: тесты должны обеспечивать 100% покрытие тестируемых функций по строкам.

**Важно**: решения должны быть построены на базе [шаблона Webpack](/ci-template).

В личном кабинете на сайте [netology.ru](http://netology.ru/) в поле комментария к домашней работе вставьте ссылки на ваш GitHub-проекты.

---

## Никнеймы

### Легенда

Вы проанализировали логи вашей игры и заметили, что многие пользователи используют «мусорные» логины и различные непонятные символы не только в никнеймах, но и в именах. Необходимо с этим что-то делать! 

### Описание

Реализуйте класс `Validator` с методом `validateUsername`, который проверяет имя пользователя с помощью регулярных выражений на соответствие следующим правилам:
1. Допустимы только латинские буквы, символы тире `-`, подчёркивания `_` и цифры (0-9);
1. Имя не должно содержать подряд более трёх цифр, а также начинаться и заканчиваться цифрами, символами подчёркивания или тире.

Не забудьте написать unit-тесты, которые обеспечивают 100% покрытие функций и классов, которые вы тестируете.



