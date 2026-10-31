#  Chota Dukan

<p align="center">
  <img width="70%" alt="screencapture-127-0-0-1-5500-index-html-2026-10-26-12_38_49" src="https://github.com/user-attachments/assets/525cea7a-8164-460e-aa22-950ec832743e" />

</p>

<p align="center">
  <b>Ek file, poora dukan.</b><br>
  Offline-first POS & inventory app for small shopkeepers — sales, purchases, udhar ledger, barcode scan, reports, backup — sab kuch ek hi HTML file mein.
</p>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-4.2-blue">
  <img alt="Size" src="https://img.shields.io/badge/size-~85_KB-success">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-green">
  <img alt="Dependencies" src="https://img.shields.io/badge/dependencies-0-brightgreen">
  <img alt="Made with" src="https://img.shields.io/badge/made_with-vanilla_JS-f7df1e">
</p>

---

##  Screenshots

<p align="center">
  <img width="30%" alt="screencapture-127-0-0-1-5500-index-html-2026-10-26-12_38_49" src="https://github.com/user-attachments/assets/525cea7a-8164-460e-aa22-950ec832743e" />
  <img width="30%" alt="screencapture-127-0-0-1-5500-index-html-2026-10-26-12_42_27" src="https://github.com/user-attachments/assets/9fc3a0da-1d9e-4928-9c5a-3fedb1fd9d72" />
  <img width="30%" alt="screencapture-127-0-0-1-5500-index-html-2026-10-31-15_55_04" src="https://github.com/user-attachments/assets/e5736b27-4d5f-40c2-8788-b0fd1f3a78ec" />

</p>
<p align="center">
  <img width="30%"  alt="screencapture-127-0-0-1-5500-index-html-2026-10-31-16_21_50" src="https://github.com/user-attachments/assets/a774cacb-41af-4362-9acc-22904d22fd07" />
  <img width="30%" alt="screencapture-127-0-0-1-5500-index-html-2026-10-31-15_55_39" src="https://github.com/user-attachments/assets/86267423-94d8-47e9-96b5-f3da1e7f98b3" />
  <img width="30%" alt="screencapture-127-0-0-1-5500-index-html-2026-10-31-16_18_04" src="https://github.com/user-attachments/assets/72870d7c-2c8f-47fd-8e3e-9dd0e3fb6fff" />

</p>

---

##  Features

| Feature | Description |
|---|---|
|  **Bikri / Khareed** | Sale & purchase with cart, discount, paid/remaining |
|  **Udhar Ledger** | Customer & supplier balances auto-calculated |
|  **Barcode Scanner** | `html5-qrcode` — camera se scan (torch + zoom) |
|  **Box / Piece System** | Pieces per box support, auto box calculation |
|  **Kg / Liter Sizes** | 250g, 500g, 1kg, 1.5L etc. quick select |
|  **Reports** | Daily / 7d / 30d / monthly profit-loss chart |
|  **Dead Stock Alert** | 30+ din se na bike items auto-flag |
|  **Categories** | Group products, per-category analytics |
|  **Backup / Restore** | One-click JSON download & upload |
|  **3 Languages** | Roman Urdu, English, اردو (RTL) |
|  **Dark Mode** | Auto-saved preference |
|  **Mobile-First** | Bottom navigation, sheets, PWA-ready |
|  **100% Offline** | Data in `localStorage`, no server needed |

---

##  Quick Start

### Option 1 — Sirf file khol lein
1. `index.html` download karein
2. Browser mein double-click karein
3. Bas! 

> ⚠️ Barcode scanner ke liye **HTTPS** zaroori hai (localhost ya GitHub Pages fine hai).

### Option 2 — GitHub Pages par host karein
1. Ye repo fork / clone karein
2. **Settings → Pages → Source: `main` branch → `/root`** select karein
3. Live URL: `https://<username>.github.io/chota-dukan/`
4. Mobile browser mein kholein → **"Add to Home Screen"** → app ki tarah chale ga 

---

##  Kaise Use Karein

| Tab | Kaam |
|---|---|
|  **Home** | Aaj ki bikri, lena/dena, monthly summary |
|  **Stock** | Products list, categories, dead stock |
|  **Bech** (center FAB) | Nai sale shuru karein |
|  **Udhar** | Customers/suppliers ke baqaya |
|  **Hisab** | Ledger + payment record |

**Barcode Scan:** Top-right 🏷️ icon ya sale form mein "Scan" button → camera kholo → barcode frame ke andar rakho.

**Backup lena:** Settings → "Backup Download" → JSON file save ho jaye. Har hafte lena best hai.

---

##  Tech Stack

- **HTML5 + CSS3** — no framework, no build step
- **Vanilla JavaScript** — single file, ~3500 lines
- **[Bootstrap 5.1](https://getbootstrap.com/)** — grid & utilities
- **[Font Awesome 6](https://fontawesome.com/)** — icons
- **[Chart.js](https://www.chartjs.org/)** — reports chart
- **[html5-qrcode 2.3.8](https://github.com/mebjas/html5-qrcode)** — barcode scanning
- **localStorage** — data persistence (unlimited, browser-based)

---

##  Project Structure
