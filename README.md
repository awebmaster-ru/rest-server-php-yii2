<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">Базовый REST API средствами Yii2</h1>
    <br>
</p>

1. Установлен шаблон basic
2. Создана пустая БД и подключена в db.php
3. Добавлена и выполнена миграция по созданию таблицы Film
4. Настроены конфигурации в web.php `urlManager`, `parsers`
5. Создана модель Film с помощью gii
6. Создан контроллер FilmController.php
7. Создана коллекция в Postman для тестирования запросов GET/POST/PUT/PATCH

Структура проекта
-------------------

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources



Требования
------------

PHP 5.6.0 +
MySql


Установка
------------

1. Склонируйте репозиторий
2. Создайте пустую БД и настройте строку подключения в db.php
3. Выполните миграции yii migrate
4. Запустите веб-сервер (OpenServer/xampp/lamp) или разверните в docker контейнере (инструкция по запросу)
5. Импортируйте в Postman коллекцию из /Postman и запустите запросы