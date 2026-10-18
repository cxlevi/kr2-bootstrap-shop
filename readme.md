# TechStore — интернет-магазин электроники (Bootstrap)

## Контрольная работа №2
**Тема:** «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Краткое описание проекта
Многостраничный сайт интернет-магазина электроники **TechStore**, разработанный с использованием CSS-фреймворка **Bootstrap 5.3.8**. Проект реализует каталог товаров, страницу товара с характеристиками, форму оформления заказа и модальные окна. Предметная область соответствует контрольной работе №1, но реализация выполнена полностью на Bootstrap с собственными доработками в `custom.css`.

## Используемый фреймворк
**Bootstrap 5.3.8** (https://getbootstrap.com/)

## Способ подключения Bootstrap
В проекте Bootstrap подключён **локально** (без использования CDN). Файлы фреймворка размещены в папке `vendor/bootstrap/`.

Используются:
- `vendor/bootstrap/css/bootstrap.min.css` — минифицированная версия стилей.
- `vendor/bootstrap/js/bootstrap.bundle.min.js` — JS Bundle, включающий Bootstrap JS и Popper.js (необходим для работы navbar, modal, accordion, toast).


Файл custom.css подключается строго после Bootstrap для корректного переопределения стилей.
Структура проекта

kr2-bootstrap-shop/
index.html              
catalog.html                 
product.html                     
order.html                       
css/
custom.css   

images/     

vendor/
bootstrap/
css/
bootstrap.min.css  
js/
bootstrap.bundle.min.js 

README.md                           
.gitignore

Репозиторий: https://github.com/cxlevi/kr2-bootstrap-shop

Автор
ФИО: Золин Никита
Группа: ЭФБО-13-25