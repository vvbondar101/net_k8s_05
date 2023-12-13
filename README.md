# Домашнее задание к занятию Troubleshooting

## Задание. При деплое приложение web-consumer не может подключиться к auth-db.  
Смотрим логи пода web-consumer и видим ошибку
curl: (6) Couldn't resolve host 'auth-db'

Приложение не может подключиться в поду в другом namespace.
Исправляем DNS адрес на auth-db.data и доступ появляется.
![01](/images/01.png)

