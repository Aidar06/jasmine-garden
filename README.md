# Jasmine Garden

Отдельный статический шаблон свадебного сайта в винтажной ботанической стилистике с арочными формами.

## Локальный запуск

```powershell
npm run dev
```

Откройте `http://127.0.0.1:4200/12`, где `12` — тестовый `public_id` приглашения в Xano.

## Проверка

```powershell
npm run check
```

Данные загружаются через `GET https://x8ki-letl-twmt.n7.xano.io/api:X8-e2j1w/priglosi/{public_id}`. RSVP отправляется через `POST /priglosi/{public_id}/rsvp`.

Проект готов к развёртыванию на Vercel.
