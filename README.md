# Тестовое задание (верстка)

Сверстанный макет: https://nodlik.github.io/test-layout/

## Использованные технологии
NPM + Sass

Для наименования классов (блоки и элементы) частично использовалась методология БЭМ. Но я бы конечно предпочитал, по возможности, использовать css modules или что-то подобное.

## Структура папок

- public
- - index.html - основной html файл
- - style/ - папка с собранным css файлом
- - img/ - использованные изображения
- src
- - index.scss - основной файл Sass
- - var.scss - список используемых sass переменных
- - media.scss - размеры экрана для медиа запросов
- - components/ - папка со стилями на каждый отдельный компонент (один блок - один компонент)
- - containers/ - папка со стилями на контейнеры компонетов (содержащие и управляющие несколькими компонетами)

В папках components и containers названия файлов строго соответствуют названию класса блока. Один блок - один файл.

## Основные компоненты

* `logo-block` - блок в шапке сайта с логотипом и ссылками (по макету не ясно - ссылки это или нет).
* `navbar` - блок навигации. Представляет собой горизонтально расположенные ссылки
* `user-button` - блок с иконкой пользователя в шапке сайта. Сделан в виде кнопки, но по макету так же не очень ясно его конкретное назначение.
* `button` - кпопка. Доступные модификаторы: `button_primary` - основная кнопка (синего цвета), `button_light` - светлая кнопка
* `blogger-info` - блок с информацией о блоггере (фото, кол-во подписчиков, текст)
* `avg-info` - блок показывающий среднее кол-во охватов
* `user-stat-block` - блок показывающий какую-либо информацию о статистике аудитории

## Основные контейнеры компонентов
* `header` - Шапка сайта с блоком навигации
* `actions` - Список кнопок и заголовка "Моя карточка"
* `main` - Основной контент страницы
* `blogger-stat` - Информация о блоггере и статистика аудитории (сверстано как grid)
* `ad-format` - Информация о рекламе
* `ad-format` - Таблица цен и услуг
* `footer` - Футер сайта

## Общая информация
Верстка сделана под все современные браузеры, без поддержки IE (только Edge).

В макете не было дизайна для адаптивной верстки, сделал минимально рабочий вариант.

___

Олег,
oleg.litovski9@gmail.com