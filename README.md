# YouTalk Blog

Адаптивная вёрстка блога сервиса YouTalk по макету Figma.

## Макет

[Figma — YouTalk Blog (Copy)](https://www.figma.com/design/85xtXl3Xzilj3wj2SLEl9Z/Youtalk---Blog--Copy-?node-id=0-1)

## Страницы

- `index.html` — главная страница блога с фильтрами и карточками статей
- `article.html` — страница статьи с контентом и боковой колонкой

## Технологии

- HTML5 (семантическая разметка)
- CSS3 (БЭМ, Flexbox, CSS Grid, media queries)
- SVG-иконки и PNG-изображения из макета

## Как открыть

1. Склонируйте репозиторий
2. Откройте `index.html` в браузере

Дополнительная сборка не требуется.

## Структура

```
css/
  base.css      — переменные, reset, общие компоненты
  header.css    — шапка и бургер-меню
  main.css      — главная страница
  footer.css    — подвал
  article.css   — страница статьи
icons/          — SVG-иконки
images/         — PNG и SVG-иллюстрации
```

## Адаптив

- Desktop: от 1200px
- Tablet: 768px – 1199px
- Mobile: до 767px
