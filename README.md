# Symphony_news_crud_panel дата написания 08.05.2018

Был написан тестовый сайт для хранения, добавления новостей. Использовались Symfony 3.4, Propel 2, Bootstrap, Twig, OpenServer. Основные функции доступные на сайте: поиск по характеристикам новости (только полное совпадение), CRUD функции. Присутствуют фейковые даные для тестирования функционала (fixture).

## Установка

Установка пакетов делается командой composer install.

Предполагается что БД будет называться news, а таблица article.

Запустить можно на внутреннем сервере php командой php bin/console server:run.

Заполнение БД фейковыми данными делается командой php app/console propel:fixtures:load.
