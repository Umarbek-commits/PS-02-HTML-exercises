
# Assignments: Name Surname — Static Website (Practice Session)

Эта папка содержит статический сайт с карточками заданий (Section 1 и Section 2, по 20 заданий в каждой секции).
Каждая карточка ведёт на собственную HTML-страницу для решения задания.

## Что я сгенерировал
- `index.html` — главная страница со списком заданий.
- `styles.css` — стили для сайта.
- `pages/sectionX-assignmentY.html` — 40 страниц (2 секции × 20 заданий).
- `README.md` — этот файл.
- `.gitignore` — рекомендуемое содержимое (создан автоматически).

## Инструкция: как подготовить репозиторий и опубликовать на GitHub Pages

1. Создайте новый репозиторий на GitHub (например `assignments-website`) — *без* README, чтобы можно было запушить локальные файлы.
2. В локальной папке выполните (в терминале):
```bash
cd path/to/assignments-website
git init
git add .
git commit -m "Initial: static assignments website"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```
3. На GitHub: Откройте страницу репозитория → Settings → Pages (или Code and automation → Pages) → Source: `main` branch → `/ (root)` → Save.
   GitHub Pages опубликует сайт по адресу: `https://<your-username>.github.io/<your-repo>/` — ждите несколько минут.

4. Проверка локально: просто откройте `index.html` в браузере (двойной клик) или запустите локальный сервер:
```bash
# python 3
python -m http.server 8000
# затем откройте http://localhost:8000 в браузере
```

## Полезные советы
- Все ссылки внутри сайта — относительные, поэтому GitHub Pages будет правильно обслуживать их из корня репозитория.
- Если хотите — можно заменить содержимое каждой страницы заданий реальными условиями и решениями.
- Если нужно, помогу: создать шаблон решения на Markdown и сгенерировать более богатые страницы (код, тесты, изображения).
