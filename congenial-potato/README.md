# Проект для нагрузочного тестирования
Сайт для проведения тестирования производительности предоставлен https://github.com/Evgeniy-Varlamov/FS21-diplom

# Запуск проекта
## Предварительные условия
На компьютере должено быть установлено следующее ПО:
1. docker -  Скачать и установить можно с помощью официального сайта https://www.docker.com/get-started
2. docker-compose -  Скачать и установить можно с помощью официального сайта https://docs.docker.com/compose/install/
3. git - Скачать и установить можно с помощью официального сайта https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git

## Установка репозитория на компьютер
    git clone https://github.com/mshegolev/congenial-potato.git
    cd congenial-potato
## Запуск проекта, параметр -d запускает контейнеры в режиме сервиса 
    cd cinema
    docker-compose up -d
## Остановка проекта
    cd cinema
    docker-compose down

После запуска 3 контейнеров можно перейти на сайт в барузере по адресу http://localhost:8000
Для доступа к панели администратоар сайта http://localhost:8000/admin
Для доступа к phpadmin http://localhost:8081
