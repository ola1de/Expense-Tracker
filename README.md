# Expense Tracker 💰

A **fully offline, cross-platform desktop expense tracker** built with Electron. Track your daily expenses, visualize spending with interactive charts, and export your data to Excel — all without ever needing an internet connection.

![Expense Tracker Screenshot](https://via.placeholder.com/1200x700/0f172a/22c55e?text=Expense+Tracker+Dashboard)

---

## ✨ Features

- 📊 **Interactive Dashboard** — Real-time charts powered by Chart.js
- 💾 **100% Offline** — All assets bundled locally, no CDN calls, no telemetry
- 📁 **Excel Export / Import** — Built-in XLSX support via SheetJS
- 🎨 **Modern Dark UI** — Inter font + Font Awesome icons, all bundled
- 🔒 **Sandboxed Renderer** — `contextIsolation: true`, `nodeIntegration: false`
- 🪟 **Windows Installer** — Ships as a single `.exe` via Inno Setup
- 💼 **Lightweight** — Single-window 1400×900 app, ~150 MB unpacked

---

## 🚀 Download

Grab the latest Windows installer from the [**Releases**](../../releases) page:

➡️ **[Download ExpenseTracker-Setup-1.0.0.exe](../../releases/latest)**

> Windows 10 / 11 (x64). Run the installer, choose your install folder, and you're done.

---

## 🛠️ Build From Source

### Prerequisites
- [Node.js](https://nodejs.org/) 18+
- [Inno Setup 6](https://jrsoftware.org/isdl.php) (Windows installer only)

### Steps
```bash
git clone https://github.com/<your-username>/expense-tracker.git
cd expense-tracker
npm install
npm start          # run in dev
npm run package    # build win-unpacked folder
```

Then open `ExpenseTracker.iss` in **Inno Setup Compiler** and press **F9** to produce the installer.

---

## 📂 Project Structure

```
expense-tracker/
├── app/
│   ├── index.html         # Full UI (HTML + CSS + JS)
│   └── vendor/            # Bundled Chart.js, XLSX, Font Awesome, Inter font
├── main.cjs               # Electron main process
├── package.json
├── ExpenseTracker.iss     # Inno Setup script
└── README.md
```

---

## 🤝 Contributing

PRs welcome! Fork, branch, commit, and open a Pull Request.

## 📜 License

[MIT](LICENSE) © 2026 ola1de
