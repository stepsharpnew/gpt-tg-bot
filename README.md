# Telegram Bot with Yandex GPT API

Это Telegram-бот, использующий библиотеку **Telegraf** для работы с **Telegram API**. Бот интегрирован с **Яндекс GPT API**, позволяя генерировать текст и картинки по запросу пользователя.

## Функции

- Обработка сообщений с помощью Telegram API.
- Генерация текста с использованием Яндекс GPT API.
- Генерация изображений через Яндекс GPT API.
  
## Требования

- Node.js версии 14 и выше.
- Наличие токена Telegram бота.
- Ключ API для Яндекс GPT.

## Установка

1. Перейдите в папку проекта:
   ```bash
   cd /путь/к/проекту

2. Установите зависимости:
   ```javascript
   npm install

3. Получите YandexGPTToken и BotToken, вставьте их в переменное окружение .env в корне проекта:
   ```javascript
   BOT_TOKEN = "your_bot_token"
   GPT_API_KEY = "your_yandex_token"
4. Запуск бота
   ```javascript
   node index.js
