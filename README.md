# api_yatube

### Описание:

Реализация API для приложения. Использована аутентификация по токенам.

### Технологии:

Python 3.7, DRF, JWT, pytest

### Как запустить проект:

Клонируй репозиторий и перейди в него в командной строке:

`git clone <link>`
`cd api_yatube`

Cоздай и активируй виртуальное окружение:

`python -m venv venv`

* Если у тебя Linux/macOS

    ```
    source venv/bin/activate
    ```

* Если у тебя windows

    ```
    source env/scripts/activate
    ```

Установи зависимости из файла requirements.txt:

`python -m pip install --upgrade pip`
`pip install -r requirements.txt`

Выполни миграции:

`cd api_yatube`
`python3 manage.py migrate`

Запусти проект:

`python manage.py runserver`


### Автор:

[Сергей Патраков](https://github.com/sergeypatrakov)