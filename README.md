# Психоматрица · Квадрат Пифагора

Бесплатный онлайн-калькулятор **Квадрата Пифагора** (нумерологическая психоматрица по дате рождения) с расшифровкой всех ячеек, рабочих чисел и линий. Без бэкенда, без регистрации — чистый статический сайт.

## Демо (GitHub Pages)

| Страница | Ссылка |
|----------|--------|
| Квадрат Пифагора (главная) | https://regulus12qqw2.github.io/psychomatrix/ |

## Что внутри

- **index.html** — расчёт психоматрицы по дате рождения. Калькулятор + расшифровка характера, энергии, интересов, здоровья, логики, труда, удачи, долга, памяти и производных чисел (Плотское, Цель, Семья, Стабильность, Самооценка, Быт, Талант, Духовное).
- **.github/workflows/pages.yml** — автодеплой на GitHub Pages при push в `master` / `main`.

## Стек

- Чистый HTML / CSS / JavaScript, без фреймворков и сборщиков
- Тёмная и светлая темы (auto по `prefers-color-scheme`)
- Glassmorphism UI, OKLCH-палитра, адаптив до 360 px

## Локальный запуск

Сайт полностью статический — открыть `index.html` в браузере или поднять любой статик-сервер:

```bash
# Python
python -m http.server 8000

# Node (если установлен npx)
npx serve .
```

Затем открой http://localhost:8000/

## Деплой

Деплой автоматический через GitHub Actions:

```bash
git add .
git commit -m "feat: описание изменения"
git push origin master
```

Workflow `Deploy to GitHub Pages` соберёт артефакт из корня репо и зальёт на Pages. Историю деплоев смотри во вкладке **Actions** → https://github.com/Regulus12qqw2/psychomatrix/actions

## Структура

```
psychomatrix/
├── index.html               # Квадрат Пифагора · ~1600 строк
├── README.md
├── .gitignore
└── .github/
    └── workflows/
        └── pages.yml        # GitHub Pages deploy
```

## License

MIT
