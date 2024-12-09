# Проектная работа Mesto

**Студент**: Nikita Prokhorov\
**Стэк**: HTML, CSS, JavaScript

## Описание проекта

**Mesto** — это проект, реализующий функционал динамического списка карточек, которые можно добавлять, редактировать и удалять. Также имеется возможность просматривать изображения карточек в модальном окне. Проект использует чистые HTML, CSS и JavaScript без библиотек или фреймворков.

## Функциональность

1. Все карточки, полученные с сервера, создаются корректно.
2. Корзина удаления присутствует только на карточках, созданных текущим пользователем.
3. В активном состоянии находятся «лайки», которые установлены текущим пользователем.
4. Форма добавления карточки открывается, добавляет карточку.
5. Работает нажатие на кнопку «лайка».
6. Реализовано удаление карточки.
7. Для всех полей ввода в формах включена лайв-валидация.
8. Кнопка отправки формы неактивна, если хотя бы одно из полей не проходит валидацию.
9. Карточку можно добавить из любого текстового поля нажатием Enter.
10. Слушатель событий, который закрывает модальное окно по нажатию на Esc, добавляется при открытии модального окна и удаляется при его закрытии.

## Технологии

- HTML5
- CSS3
- JavaScript (ES6)
- API (using fetch)
- Live form validation
- BEM Nested

## Установка и запуск

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/kmuradoff/mesto-project.git
    ```
2. Установить **NPM** (_Node Package Manager_) — менеджер пакетов для программной платформы Node.js.
   ```bash
    npm i
   ```
3. Собрать проект
   ```bash
   npm build
   ```
4. Запустить проект в режиме разработчика
   ```bash
   npm run dev
   ```
## Просмотр проекта через GitHub Pages
https://antihype320.github.io/mesto-project/