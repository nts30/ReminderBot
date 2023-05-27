# Reminder Bot
Этот проект помогает сохранить напоминания в базе данных при помощи телеграмм-бота. Также предоставляет 
простой REST API для обращения к базе данных и извлечения и/или добавления напоминания.

## Установка

1. Склонировать репозиторий:
    ```shell
   git clone https://github.com/nts30/ReminderBot/blob/master
   
2. Установка библиотек и модулей:
   ```shell
   pip install requirements.txt

3. Создание и активация виртуального окружения(Window):
   ```shell
   python -m venv venv
   cd venv\Scripts
   activate.bat
   
4. Изменения в config\config.ini:
* **BOT_TOKEN** - Токен бота у @FatherBot
* **HOST_URL** - Ссылка на домен 
* **ADMIN_ID** - ID администратора бота Telegram
* **TIMEDELTA** - Отклонение локального времени от серверного (в часах)

## Запуск проекта

Запуск app\main.py
   ```shell
   uvicorn app.main: app --reload
   ```
## Контакты
Baton_Lexa

**Telegram:** [Baton_Lexa](https://t.me/Baton_Lexa)