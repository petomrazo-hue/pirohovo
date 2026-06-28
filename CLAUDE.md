# Pirohovo

Web fastfood reštaurácie Pirohovo v Bratislave. Dark cinematic design, WhatsApp ordering, plné menu.

## Deploy
```bash
git add . && git commit -m "..." && git push
```
- Live: **pirohovo.eu** (GitHub Pages + Cloudflare)
- GitHub: PUBLIC repo, push na main = deploy

## Kľúčové pravidlá
- Logo: **images/wordmark.png** — reálne vystrihnuté z logo.jpg (PIROHO♥O). **NIKDY neprekresľuj fontom!**
- Font: **Amatic SC**
- "VO VÝSTAVBE" overlay: `UC_ON=true/false` v `construction.js`; klientský náhľad `?nahlad=pirohy2026`
- Rozvoz badge: zobrazovať **len keď otvorené** (nie Zatvorené+Rozvoz naraz)
- Emoji v UI: nahradiť Lucide SVG ikonami

## PENDING
- GA4 tracking ID doplniť
- Google Ads konverzný label
- Cookies live ID

## Easter egg
- Klik na logo = 52 padajúcich pirohov (len egg, nie ambient)
