# taskbot-app

Telegram Mini App для бота поручений: статическая страница (GitHub Pages, https://app.saq-tech.kz). Без данных и ключей.

- `index.html` — вся страница: разметка, стили и код, без сборки и сторонних библиотек (кроме `telegram-web-app.js` от Telegram).
- Данные — только из API бота: `https://api.saq-tech.kz` (рабочий бот) или `https://api-test.saq-tech.kz` (стенд, адрес страницы с `?env=test`). Других адресов страница не знает.
- Вход — подписью Telegram (`initData`) на каждом запросе; права — те же, что в личке с ботом.
- `CNAME` — адрес страницы для GitHub Pages.

Решение и устройство — ADR-022 и ARCHITECTURE 3.1 в репозитории бота.
