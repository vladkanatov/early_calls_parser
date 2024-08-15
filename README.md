# Telegram Link Collector Bot

Этот проект представляет собой телеграм-бота, который собирает ссылки из сообщений канала Telegram за указанный вами период. Бот использует библиотеку `aiogram` для работы с Telegram Bot API и `pyrogram` для работы с Telegram API.

## Функциональность

- Позволяет пользователю указать период (начальная и конечная дата) для сбора ссылок.
- Сохраняет уникальные ссылки, найденные в сообщениях канала, в текстовый файл.
- Отправляет файл с собранными ссылками обратно пользователю в Telegram.

## Установка

1. **Клонируйте репозиторий:**

    ```sh
    git clone https://github.com/lon8/early_calls_parser
    cd early_calls_parser
    ```

2. **Создайте и активируйте виртуальное окружение:**

    ```sh
    python3.11 -m venv venv
    source venv/bin/activate  # Для Windows используйте: venv\Scripts\activate
    ```

3. **Установите зависимости:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Зайдите в файл `main.py`. В нем должны быть следующие переменные:**

    ```
    API_TOKEN=ваш_токен_бота
    API_ID=ваш_API_ID
    API_HASH=ваш_API_HASH
    CHANNEL_ID=ID_канала_или_username
    ```

## Настройка

1. **Получите токен вашего Telegram-бота, а также `API_ID` и `API_HASH` от [Telegram API](https://my.telegram.org/auth).**

2. **Замените значения в переменных `API_TOKEN`, `API_ID`, `API_HASH`, и `CHANNEL_ID` в вашем коде на полученные данные.**

3. **Проверьте и убедитесь, что бот добавлен в нужный канал с разрешением на чтение сообщений.**

## Запуск

Для запуска бота выполните следующую команду:

```sh
python main.py

# Telegram Link Collector Bot

Этот проект представляет собой телеграм-бота, который собирает ссылки из сообщений канала Telegram за указанный вами период. Бот использует библиотеку `aiogram` для работы с Telegram Bot API и `pyrogram` для работы с Telegram API.

## Функциональность

- Позволяет пользователю указать период (начальная и конечная дата) для сбора ссылок.
- Сохраняет уникальные ссылки, найденные в сообщениях канала, в текстовый файл.
- Отправляет файл с собранными ссылками обратно пользователю в Telegram.

## Установка

1. **Клонируйте репозиторий:**

    ```sh
    git clone <URL-репозитория>
    cd <название-папки>
    ```

2. **Создайте и активируйте виртуальное окружение:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # Для Windows используйте: venv\Scripts\activate
    ```

3. **Установите зависимости:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Создайте файл `.env` для хранения конфиденциальных данных, таких как токены и ключи API. В нем должны быть следующие переменные:**

    ```
    API_TOKEN=ваш_токен_бота
    API_ID=ваш_API_ID
    API_HASH=ваш_API_HASH
    CHANNEL_ID=ID_канала_или_username
    ```

## Настройка

1. **Получите токен вашего Telegram-бота, а также `API_ID` и `API_HASH` от [Telegram API](https://my.telegram.org/auth).**

2. **Замените значения в переменных `API_TOKEN`, `API_ID`, `API_HASH`, и `CHANNEL_ID` в вашем коде на полученные данные.**

3. **Проверьте и убедитесь, что бот добавлен в нужный канал с разрешением на чтение сообщений.**

## Запуск

Для запуска бота выполните следующую команду:

```sh
python main.py

## Использование
1. **Отправьте команду `/start` боту в Telegram.**
2. **Введите начальную дату в формате ДД.ММ.ГГГГ ЧЧ:ММ, например, `12.08.2024 12:38`.**
3. **Введите конечную дату в том же формате.**
4. **Бот начнет собирать ссылки за указанный период и отправит файл с собранными ссылками в ответ.**


Если у вас возникли вопросы или предложения, не стесняйтесь обращаться!