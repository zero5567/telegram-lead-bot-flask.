# telegram-lead-bot-flask.
# 🤖 Telegram Bot for Lead Generation (Python + Flask)

Готовое plug-and-play решение для бизнеса: Telegram-бот для приёма заявок и консультаций с интеграцией вебхуков и автоматическим развёртыванием на PythonAnywhere.

## 🚀 Функционал
- **Интерактивное меню:** Быстрый доступ к услугам и ценам через `ReplyKeyboardMarkup`.
- **Сбор заявок:** Пошаговый сбор контактов и суть задачи от клиента.
- **Уведомления администратору:** Мгновенная пересылка входящих заявок в личные сообщения администратора.
- **24/7 Uptime:** Настроена работа через Webhook без необходимости держать локальный ПК включенным.

## 🛠 Технологии
- Python 3.13
- Flask
- Requests (работа через HTTP Webhook API)
- PythonAnywhere (Hosting)

## 📦 Инструкция по развертыванию
1. Клонируйте репозиторий.
2. Укажите ваш `TOKEN` от @BotFather и `ADMIN_ID` в файле `app.py`.
3. Загрузите файл на PythonAnywhere в раздел WSGI.
4. Установите Webhook через браузер:
   `https://api.telegram.org/bot<YOUR_TOKEN>/setWebhook?url=https://<YOUR_USERNAME>.pythonanywhere.com/<YOUR_TOKEN>`

---
📧 **Контакты для заказа:** [Telegram: @Nurikxzy]
