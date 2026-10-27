# Контрольная работа №2

> ### 👤 Тихомиров Иван Русланович
> 🎓 **Группа:** ЭФБО-06-25  
> 🔗 **Репозиторий:** [github.com/dizzy-go/kr2-bootstrap-shop](https://github.com/dizzy-go/kr2-bootstrap-shop)  
**Опубликованная версия (GitHub Pages):** [https://dizzy-go.github.io/kr2-bootstrap-shop/](https://dizzy-go.github.io/kr2-bootstrap-shop/)


**Тема:** «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

---

## Описание проекта

Проект представляет собой учебную версию сайта интернет-магазина (каталога товаров), разработанную с использованием Bootstrap. Проект включает главную страницу, каталог, страницу товара и страницу заявки. Интерфейс полностью адаптируется под мобильные, планшетные и desktop-экраны.

## Используемый фреймворк и способ подключения

**Фреймворк:** Bootstrap 5.3.3.

**Способ подключения:** Bootstrap подключён **локально**. Файлы фреймворка размещены в папке `vendor/bootstrap/`.

Используются:
- `vendor/bootstrap/css/bootstrap.min.css`;
- `vendor/bootstrap/js/bootstrap.bundle.min.js`.

Собственный файл `css/custom.css` подключён после Bootstrap CSS для возможности переопределения стилей.

## Структура проекта

```text
kr2-bootstrap-shop/
├── index.html
├── catalog.html
├── product.html
├── order.html
├── css/
│   └── custom.css
├── images/
│   ├── product-1.jpg
│   ├── product-2.jpg
│   └── product-3.jpg
├── vendor/
│   └── bootstrap/
│       ├── css/
│       │   └── bootstrap.min.css
│       └── js/
│           └── bootstrap.bundle.min.js
├── README.md
└── .gitignore