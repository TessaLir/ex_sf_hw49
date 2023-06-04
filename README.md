﻿# Практическое задание к модулю 49

## Задание:

1. Воспроизведите MVC-архитектуру согласно полученным знаниям, на примере сайта визитки – 5 баллов
Можно использовать шаблонизатор TWIG. 

1. Подключите пакет php-gd, прикрепить скрин о его подключении (phpinfo) – 10 баллов

1. Реализуйте в вашем приложении несколько статических страниц (“О нас», «Контакты» и т.д.) – 20 баллов


## Результат

1. Реализован MVC на примере сайта визитки с прошлого урока.

    TWIG не использовался...

1. Скриншот Установленного php-gd: 

    ![Скриншот установленного GD](./Images/GD.png)

    ---

1. Созданы страницы:

    Модель есть только у [Партнеров](./Application/Models/model_partner.php)

    <br>

    Контроллер:
    - [О нас](./Application/Controllers/controller_about.php)
    - [Контакты](./Application/Controllers/controller_contact.php)
    - [Партнеры](./Application/Controllers/controller_partner.php)

    <br>

    Представление:
    - [О нас](./Application/Views/about_view.php)
    - [Контакты](./Application/Views/contact_view.php)
    - [Партнеры](./Application/Views/partner_view.php)
