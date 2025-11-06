# NoirCard — Лендинги с картинками (готово к публикации)

## Структура
- `index.html` — выбор версии
- `v1/index.html` — тёмный премиум (использует `assets/hero.svg`, `before.svg`, `after.svg`)
- `v2/index.html` — светлый минимализм (те же изображения)
- `assets/*` — ваши картинки (SVG сейчас-плейсхолдеры)

## Быстрый старт
1. Создайте новый публичный репозиторий, например `noircard-landings-images`.
2. Загрузите все файлы из этой папки (Upload files → Commit).
3. Включите GitHub Pages: Settings → Pages → Deploy from a branch → Branch: main/основной, Folder: /(root).
4. Откройте: `https://<логин>.github.io/noircard-landings-images/`.

## Как заменить картинки
- Положите свои `PNG/JPG/SVG` в папку `assets/`.
- Сохраните имена файлов: `hero.svg`, `before.svg`, `after.svg` — тогда **ничего в коде менять не надо**.
- Или отредактируйте `v1/index.html` и `v2/index.html`, если захотите другие имена.

Параметры `?src` и UTM автоматически приклеиваются к кнопкам Telegram/WhatsApp/Form.
