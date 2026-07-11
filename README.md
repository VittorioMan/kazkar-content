# kazkar-content

Статичний каталог книжок застосунку **Казкар** (GitHub Pages).

- `catalog.json` — індекс: `books[].{id,title,baseUrl,cover,free,version}`.
- `books/<id>/` — `manifest.json` (uk, фолбек) [+ `manifest.en.json`] + `cover` + `pNN.jpg`.
- `version` (книжки і каталогу) — на майбутнє для оновлення кешу; поточний клієнт ігнорує.
- Схема — дзеркало bundled-книжок застосунку; деталі в README основного репо.
