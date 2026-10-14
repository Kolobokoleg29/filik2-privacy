# FILIK2 — политика конфиденциальности

Публичная политика конфиденциальности игры **«Слова: Забытая Экспедиция»** для Android / RuStore.

- Разработчик: **Рябцев Олег**
- Контакт поддержки и по вопросам персональных данных: **kolobokoleg19@gmail.com**
- Содержимое сайта: [index.html](./index.html)
- Адрес GitHub Pages после включения публикации: https://kolobokoleg29.github.io/filik2-privacy/

## Как включить GitHub Pages

1. Открыть **Settings → Pages** для этого репозитория.
2. **Build and deployment → Source**: выбрать **Deploy from a branch**.
3. **Branch**: выбрать `main`, папка `/(root)`, затем **Save**.
4. Дождаться окончания сборки Pages и открыть ссылку выше. Проверить, что отображается политика и контакт разработчика, а не 404.

GitHub Pages публикует только эту информационную страницу. Репозиторий игры FILIK2 остаётся приватным; ключи, APK и исходники игры сюда не добавляются.

## Второй сайт в том же репозитории — разработчик / РСЯ

Действующая политика конфиденциальности по адресу https://kolobokoleg29.github.io/filik2-privacy/ остаётся в корне `index.html` и продолжает работать через GitHub Pages.

Отдельный статический сайт разработчика находится в [`developer-site/`](./developer-site/) и предназначен для публикации через **Cloudflare Pages**:

- сайт: `developer-site/index.html`;
- точный файл РСЯ: `developer-site/app-ads.txt`;
- production branch: `main`;
- build command: пусто;
- build output directory: `developer-site`.

См. [полную инструкцию по двум сайтам и подтверждению FILIK2 в РСЯ](./CLOUDFLARE_PAGES_SETUP.md). До подключения Cloudflare публичный адрес второго сайта не подтверждён, а опубликованный GitHub Pages-сайт менять не требуется.
