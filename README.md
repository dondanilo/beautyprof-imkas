# BeautyProf IMCAS 2026 — Landing Page

## Структура файлов

```
beautyprof-imkas/
├── index.html
├── images/
│   └── logo-white.png   ← ДОБАВИТЬ: белый логотип BeautyProf
└── README.md
```

## Перед деплоем

Сохрани белую версию логотипа (белый текст на тёмном фоне) как:
`images/logo-white.png`

## Деплой на GitHub Pages

1. Создай репозиторий на github.com (например: `beautyprof-imkas`)
2. Загрузи все файлы в репозиторий
3. Settings → Pages → Branch: main → Save
4. Сайт появится по адресу: `https://[твой-username].github.io/beautyprof-imkas`

## Подключение поддомена imkas.beautyprof.kz

1. В корне репозитория создай файл `CNAME` с содержимым: `imkas.beautyprof.kz`
2. В DNS панели домена beautyprof.kz добавь запись:
   - Тип: CNAME
   - Имя: imkas
   - Значение: [твой-username].github.io
3. В GitHub: Settings → Pages → Custom domain → imkas.beautyprof.kz
4. Подождать 10-30 минут на propagation DNS
