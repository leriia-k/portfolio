# Landing (based on your Figma mock)

Структура ровно как в макете:
- Шапка: слева `leriia`, справа `Resume` и кнопка `Get in Touch`.
- Hero: огромный H1 «Product Designer».
- Плитки: ряд 1 — 2 карточки (About Me, Loomy с айфоном), ряд 2 — 3 карточки (All Projects, Resume, Skills).
- Футер: кнопка Mail Me + email, справа иконки Instagram/LinkedIn.

## Где править контент
- `index.html`: тексты, ссылки, email (поиском `your@email.com`).
- `assets/iphone-top.png`: заглушка айфона (можно заменить своим PNG).
- `assets/instagram.svg`, `assets/linkedin.svg`: иконки соцсетей.

## Быстрый деплой
- **Netlify**: перетащите папку в Netlify Drop → получите URL.
- **Vercel**: импортируйте как «Static files».
- **GitHub Pages**: репозиторий → Settings → Pages.

## Встраивание в Notion (пиксель-точность)
1. В Notion: Full width + Small text.
2. Вставьте блок **Embed** со ссылкой на задеплоенный сайт.
3. В Super.so/Potion (если используете) можно добавить CSS для iFrame:
   ```css
   .notion-embed iframe{ width:100%; min-height:100vh; border:0; }
   .notion-embed{ padding:0 !important; }
   .super-content{ max-width:1140px; padding-inline:24px; }
   ```
