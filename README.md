# Algoua

![deploy](https://github.com/algoua/algoua/workflows/deploy/badge.svg?branch=main)

Алгоритмічні навчальні матеріали.

Усі статті написані у форматі Markdown з використанням LaTeX та знаходяться у папці `docs`.

## Алгоритми
Збірка алгоритмічних статей.

Структура кожної статті:

* Опис алгоритму з поясненнями та можливими доведеннями.
* Реалізація (C++).
* Застосування.
* Задачі.

## Курси

TODO

## Тестовий сервер

1. Клонування репозиторію.

        $ git clone https://github.com/algoua/algoua.git

1. Встановлення [Node.js](https://nodejs.org/en/download/) та [Yarn](https://yarnpkg.com/en/).

1. Запуск серверу. Він буде доступним за посиланням [http://localhost:3000](http://localhost:3000).

        $ yarn start

## Внесення змін

Потрібно мати налаштований локальний тестовий сервер.

Пропонуйте зміни у вигляді `pull request` з вашого `fork` репозиторію. З інструкціями як створити `pull request` можна ознайомитися [тут](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).

Markdown статті повинні бути відформатовані використовуючи soft-wrap, а не hard-wrap. Іншими словами немає обмеження на довжину рядків та не потрібно його вводити. GitHub підтримує soft-wrap, а для локального редагування використовуйте редактор, який теж його підтримує, наприклад, [VS Code](https://code.visualstudio.com/).

## Джерела

* [e-maxx](http://e-maxx.ru) (LICENSE - Public Domain).
* Різні матеріали з інтернету із сумісними ліцензіями, що не потребують згадування.
