# Full Time Wins — Expense Tracker & Database

An offline-first, client-side bookkeeping and expense tracking platform. Designed with a sleek, glassmorphic dark/light UI, **Full Time Wins** offers immediate structural setups optimized for **9 distinct business sectors**. 

Run it as a secure web app directly in any desktop browser, or compile it locally as a native Windows desktop executable.

---

## 🚀 Key Features

- **Local-First & Secure:** No databases to sync, no third-party APIs to trust. 100% of your transactional data, user profiles, and budget settings remain compiled on your local machine's `localStorage`.
- **Dynamic Sector Schemas:** Immediately generate custom input databases configured with custom parameters for multiple corporate sectors:
  - *Construction & Engineering* (Cement, sand, labor wages, machinery lease, unit variables)
  - *Real Estate & Property Management* (Properties, repairs, project phases, contractor fields)
  - *Logistics & Transport* (Vehicle IDs, vehicle fuel tracking, drivers, permits)
  - *IT Services & SaaS* (Software tools, license types, hosting platforms, billing cycle)
  - *Manufacturing, Retail, E-commerce, Hospitality, and General Business*
- **Smart Excel Output:** Integrated via **SheetJS**, exporting detailed spreadsheets alongside live formula systems (e.g. `=SUM(...)`) so you do not lose math structures during report exports.
- **Dynamic Visual Analytics:** Real-time Category Breakdown (doughnut charts) and Daily Spend trends (bar charts) powered via **Chart.js**.
- **Local Data Portability:** Download fully comprehensive structured backup files in standardized JSON formats at any time, allowing seamless restores across devices.

---

## 🛠️ Technology Stack

- **UI styling:** Glassmorphism styled via pure responsive Vanilla CSS variables (supporting live dark/light mode toggle).
- **Core logic:** Vanilla Modern JavaScript (ES6+) organized cleanly inside IIFEs to protect scope.
- **Data Rendering Engine:** Chart.js (v4+) CDN.
- **Excel parsing compiler:** SheetJS (xlsx.full.min.js v0.18.5) CDN.
- **Font & Icon libraries:** Google Fonts (Inter) and Font Awesome 6 CDN.

---

## 📂 Project Structure

```text
├── index.html         # The complete single-page application script (pure HTML, JS, and CSS)
├── LICENSE            # Open-source licensing file
└── README.md          # Documentation file
