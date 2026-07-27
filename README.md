# 🐷 Chanchito

A warm little personal‑finance companion, inspired by the Costa Rican *alcancía de barro* — the hand‑painted clay piggy bank. Track income, expenses, investments, assets, and savings goals, and watch your chanchito fill as you save.

**Live app:** _add your Vercel URL here_

## Features

- **Home dashboard** — income, spending, investments, and savings rate at a glance
- **Goals** — a clay pig that fills as you save, with milestone celebrations (*la onda*)
- **Income / Expenses / Investments / Assets** — full add, edit, duplicate, archive, delete
- **Smart regional setup** — country → currency and prefilled local prices (Costa Rica, Canada, US, UK)
- **Chanchito AI** — an on‑device advisor: subscription‑overlap tips, savings‑rate coaching, net‑worth forecasts, and a chat that answers from your own numbers
- **Month‑end review** — change recaps and a reminder to back up
- **Excel export** — month‑by‑month workbook (income, expenses, investments, assets, goals, change log)
- **Installable PWA** — add to your home screen for a full‑screen, app‑like experience

## Tech

A single self‑contained `index.html` — no build step, no dependencies, no backend. All data lives in the browser's `localStorage`; nothing leaves your device. Icons and manifest make it installable as a Progressive Web App.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 4180
```

Then visit `http://localhost:4180`.

## Deploy

Any static host works. On **Vercel**, import this repo — it serves `index.html` at the root with zero configuration.

## Privacy

Your financial data is stored only in your own browser. Use **Settings → Export** to back it up.
