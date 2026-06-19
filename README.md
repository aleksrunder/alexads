# Alexads landing page

Статический сайт для GitHub Pages: HTML + CSS + JS.

## Что заменить перед публикацией

1. В `index.html` заменить:
   - `https://your-domain.com/` на будущий домен или GitHub Pages URL.
   - `your-email@example.com`
   - `https://t.me/your_username`
   - `https://wa.me/37100000000`
2. В `privacy.html` заменить email и данные владельца сайта.
3. В `robots.txt` и `sitemap.xml` заменить `https://your-domain.com/`.
4. Если добавляешь Meta Pixel / Google Analytics:
   - обнови `privacy.html` и `cookies.html`;
   - вставляй код только в функцию `loadMarketingScripts()` в `script.js`, чтобы трекеры не запускались до согласия.

## Файлы

- `index.html` — главная страница
- `style.css` — дизайн и адаптив
- `script.js` — языки, меню, анимации, cookie consent scaffold
- `privacy.html` — политика приватности
- `cookies.html` — политика cookies
- `robots.txt` — индексация
- `sitemap.xml` — карта сайта
- `assets/alex.jpg` — фото
