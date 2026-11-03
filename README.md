# 口袋圖書館 Pocket Library

A pocket encyclopedia web app series — one book per topic, in Traditional Chinese.
Each book has search, light/dark mode, a flip-card glossary and an 8-question quiz.

## Contents

- `pocket-library/` — the library front door: hero carousel, Cover Flow shelves, search & filters
- `jazz-encyclopedia/` — Jazz
- `ai-encyclopedia/` — AI
- `ancient-egypt-encyclopedia/` — Ancient Egypt

## Adding a new book

1. Build the book as a single self-contained page.
2. Add it as a new folder next to the others (e.g. `miles-davis/index.html`).
3. Add its cover to the front door's catalogue so it appears on its shelf.

The front door links to each book as a sibling folder (`../<book>/`), so the
layout must stay flat: every book is a direct child of the repository root.
