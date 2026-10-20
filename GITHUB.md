# Выложить через GitHub Pages

GitHub Pages размещает только сам сайт (бесплатно). Общий рейтинг по-прежнему хранится в Firebase, поэтому шаги 1–3 из README.md всё равно нужны.

1. Зарегистрируйся на [github.com](https://github.com/signup) и создай репозиторий: [github.com/new](https://github.com/new).
   - Назови его `ТВОЙ-НИК.github.io`, тогда сайт откроется по адресу `https://ТВОЙ-НИК.github.io/` (так будут работать robots.txt и sitemap.xml).
   - Поставь «Public».
2. Нажми «uploading an existing file» и перетащи файлы из папки: index.html, robots.txt, sitemap.xml. Нажми «Commit changes».
3. Открой в репозитории Settings → Pages → Source: «Deploy from a branch» → ветка `main`, папка `/ (root)` → Save.
4. Через 1–2 минуты сайт откроется по адресу `https://ТВОЙ-НИК.github.io/`.
5. В [Firebase Console](https://console.firebase.google.com/) открой Authentication → Settings → Authorized domains → Add domain и добавь `ТВОЙ-НИК.github.io`. Без этого общий рейтинг не заработает.
6. Замени `ВАШ-САЙТ.web.app` на `ТВОЙ-НИК.github.io` в index.html, robots.txt и sitemap.xml и загрузи файлы заново.
7. Для Google: [Search Console](https://search.google.com/search-console), добавь адрес и отправь sitemap.xml.

Документация: [GitHub Pages](https://docs.github.com/pages/getting-started-with-github-pages/creating-a-github-pages-site)
