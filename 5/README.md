### Лабораторная работа №5

> Цель работы
>> Закрепить понимание процесса написания ролей и их конфигурирования и развертывания.
> 
>> [Подборка по Ansible](https://gitlab.com/deusops/lessons/documentation/ansible)
>
>> [Документация к PostgreSQL на русском](https://postgrespro.ru/docs/postgrespro/14/index)
>
>> [Установка от ruvds](https://ruvds.com/ru/helpcenter/postgresql-pgadmin-ubuntu/)
>
>> [Что такое pg_hba](https://postgrespro.ru/docs/postgrespro/10/auth-pg-hba-conf)
>
>> [Как работать с пользователями в Postgres](https://www.dmosk.ru/miniinstruktions.php?mini=postgresql-users)
> 
>> [Про отказоустойчивость в БД](https://postgrespro.ru/docs/postgrespro/14/high-availability)
> 
>> [Настройка репликации в Postgres](https://selectel.ru/blog/tutorials/how-to-set-up-replication-in-postgresql/)
>
>> [Управление высокодоступными PostgreSQL кластерами с помощью Patroni](https://habr.com/ru/post/504044/)
>

> Задачи:
>> * Развернуть виртуальную машину для приложения (app) и виртуальную машину для будущей системы базы данных (db) через Vagrantfile
>> * Написать роль установки PostgreSQL и плейбук, который ее разворачивает
>> * Все параметры должны быть вынесены в переменные, все переменные должны быть префиксованы, значения переменных устанавливаются через group_vars для плейбука, роль должна быть покрыта тестами
>> * Добавить возможность смены директории с данными на кастомную
>> * Добавить возможность создания баз данных и пользователей
>> * Добавить функционал настройки streaming-репликации
>> * Продумать логику определения master и replica нод СУБД и их настройки при работе роли



