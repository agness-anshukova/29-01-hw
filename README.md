# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Аншукова Ания`


### Задание 1
## Приведите примеры проблем, которые может решить кеширование

1. `экономия вычислительных мощностей: один раз созданный отчет на основе данных из БД до его инвалидации может использоваться повторно`
2. `CDN - кэширование позволяет решить проблему скорости доставки данных в случае значительной удаленности сервера и клиента`
3. `Зскорость возвращения данных пользователю (обмен с ОЗУ быстрее обмена с  диском)`


### Задание 2
## Установка и запуск memcached

![Установка и запуск memcached на ubuntu](/img/memcached_server.png)

`Установка и запуск memcached на ubuntu
![Установка и запуск memcached](/img/memcached_localhost.png)`


### Задание 3
## Запись в memcached нескольких ключей, для которых выставлен TTL 5

`Создание ключей
![Создание ключей memcached](/img/memcached_keys.png)`

`Удаление ключей
![Удаление ключей memcached](/img/memcached_keys_exp.png)`


### Задание 4
## Запись данных в Redis

`Запись значений
![Создание ключей в redis](/img/redis_keys_set.png)`

`Получение значений
![Получение значений ключей в redis](/img/redis_keys_get.png)`
