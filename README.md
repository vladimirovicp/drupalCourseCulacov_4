# Интернет магазин и портал на Drupal 9

## ddev comands
> * **Экспорт:** ddev export-db --file=./private/db/current.sql.gz
> * **Импорт:** ddev import-db --src=./private/db/ssudev.sql.gz

## Модули
> * [admin toolbar](https://www.drupal.org/project/admin_toolbar)
> * [devel](https://www.drupal.org/project/devel)
> * [token](https://www.drupal.org/project/token)
> * [pathauto](https://www.drupal.org/project/pathauto)
> * [ctools](https://www.drupal.org/project/ctools)

## Раздел 4: Коммерц(Раздел)

### 4.1 Вступление Коммерц
### 4.2 Установка коммерц и пайпал

> * [Commerce Core](https://www.drupal.org/project/commerce)
> * [Inline Entity Form](https://www.drupal.org/project/inline_entity_form) | Нужен для Commerce Core
> * [Commerce PayPal](https://www.drupal.org/project/commerce_paypal)


> * Commerce - Стартовый модуль
> * Commerce Cart - Добавляет функционал для корзины
> * Commerce Checkout - оформление корзины
> * Commerce Log - отвечает за логи
> * Commerce Number Pattern - два типа заказа
> * Commerce Order -
> * Commerce Payment - интегрировать метод оплаты
> * Commerce Payment Example - примеры
> * Commerce Price - интегрирует функционал по созданию цен, классы, методы
> * Commerce Product - Создает два типа, страница презентации и визуализация инвариации
> * Commerce Promotion - акции, скидки
> * Commerce Store - Сам интернет магазин, который создаем
> * Commerce Tax

Включаем
> * Commerce
> * Commerce Cart
> * Commerce Checkout
> * Commerce Log
> * Commerce Number Pattern
> * Commerce Order
> * Commerce Payment
> * Commerce Price
> * Commerce Product
> * Commerce Store

### 4.3 Валюта и магазин

> * Создаем валюту(../admin/commerce/config/currencies)
> * Типы магазина
> * Создаем Магазин

### 4.4 Order Type и Order Item Type
