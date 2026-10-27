# Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Описание

Проект представляет собой учебную версию сайта интернет-магазина или каталога товаров,
разработанную с использованием Bootstrap.

## Используемый фреймворк

Bootstrap 5.3.3.

## Способ подключения Bootstrap

Bootstrap подключён через CDN.

Используются:

- `https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css`;
- `https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js`.

Собственный файл `css/custom.css` подключён после Bootstrap CSS.

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
├── README.md
└── .gitignore