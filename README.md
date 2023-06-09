# Raiffeisen-Bootcamp
Homework for Raiffeisen bootcamp (DevOps)

There were 2 task.

1.Тестовое задание: Автоматизированное обновление операционной системы c помощью Ansible
(Automated operating system update using Ansible)
Включает следующие цели:

    - Написать Ansible role для обновления операционной системы.
    - Создать inventory файл, в котором создать группу servers и внести в неё свой localhost либо иной управляемый вами сервер
    - Сделать playbook для запуска написанной вами role
    - Написанную автоматизацию разместите в своем профиле github

2.Тестовое задание: Docker-контейнер для Python-скрипта
(Docker container for Python script)
Включает следующие цели:

    - Установить Docker и docker compose. Окружение не имеет значения, это может быть как ноутбук с приложением docker desktop, так и виртуальная машина.
    - Создайте Dockerfile для Python-скрипта:
        - Впишите свои ФИО и почту в файлы name.txt и mail.txt соответственно. Файлы нужно создать.
        - Используйте официальный образ Python (например, python:3.9-slim).
        - Установите зависимости из requirements.txt.
        - Копируйте все файлы из локальной директории в рабочую директорию контейнера.
        - Задайте переменную окружения CONTAINERENV со значением True.
        - Укажите команду для запуска приложения.
    - Создайте docker-compose.yml файл:
        - Определите сервис для Python-приложения, основанный на созданном Dockerfile.
        - Определите сервис для Redis.
        - Создайте сеть, которая будет использоваться для связи между контейнерами Python-приложения и Redis.
    - Убедитесь, что все работает корректно:
        - Запустите приложение с помощью docker-compose up.
        - Проверьте работоспособность веб-страницы и функционал кнопки.
        - Если после нажатия кнопки нет ошибок и есть подтверждающая надпись, то задание выполнено успешно.
