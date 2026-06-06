# AI MBA — единая веб-система

Публичная статическая сборка программы AI MBA v3.1. Деплоится на GitHub Pages.

## Структура

| Путь | Что это |
|------|---------|
| `index.html` | Лендинг программы (v3.1) |
| `portal/` | Портал слушателя |
| `tools/maturity/` | AI Maturity Self-Assessment (прототип v0.1) |

Все страницы — самодостаточные статические HTML без бэкенда.

## Локальный запуск

```bash
cd site
python3 -m http.server 8000
# открыть http://127.0.0.1:8000
```

## Деплой

Автоматически на GitHub Pages при push в `main` (см. `.github/workflows/deploy.yml`).
Кастомный домен задаётся файлом `CNAME`.
