# 🦋 My Budget Planner

A beautiful, offline-first personal budget planner that runs entirely in your browser — no accounts, no servers, no subscriptions.

🔗 **Live link: [keatyi.github.io/budget-planner](https://keatyi.github.io/budget-planner/)**

---

## ✨ Features

### 📅 Monthly Planning
- Switch between any month of the year using the month tabs
- Set your monthly income and split it across custom categories by percentage
- Track individual expenses within each category with live progress bars
- Add a monthly note for context (e.g. *Raya spending, bought a laptop*)

### 📊 Year Summary
- See all your months side by side in a single table
- Only months with data are shown — clean and uncluttered
- Cumulative totals per expense item 
- Automatically updates as you edit

### 🗂️ Category Management
- Comes with 4 default categories: Needs, Savings, Wants, Entertainment
- Fully customisable — rename, recolour, add or remove categories
- Percentage split always kept visible so you can balance your budget at a glance

### 🛠️ Utilities
- **↩ Copy last month** — carry over last month's income and amounts as a starting point
- **✕ Clear amounts** — zero out all income and expenses for the current month while keeping your labels
- **⬇ Save PDF** — export the current month's planner or the year summary as a clean PDF
- **🌙 Dark mode** — easy on the eyes, toggle anytime

### 💾 Data Persistence
- Everything is saved automatically to your browser's `localStorage`
- No internet connection required after the first load
- Export to PDF as a backup in case your browser cache is cleared

---

## 🚀 Getting Started

No installation needed.

1. Download `index.html`
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. Start entering your income and expenses

That's it.

---

## 📄 Saving as PDF

Click **⬇ Save PDF** in the top-right corner at any time.

- From the **Planner** tab → exports the current month's budget breakdown
- From the **Year Summary** tab → exports the full year table in landscape layout

In the print dialog, select **Save as PDF** as the destination. The PDF is designed to fit cleanly on a single A4 page.

---

## 🛠️ Tech Stack

| | |
|---|---|
| Framework | None — vanilla HTML, CSS, JavaScript |
| Fonts | [Shippori Mincho](https://fonts.google.com/specimen/Shippori+Mincho) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts |
| Storage | Browser `localStorage` |
| Dependencies | None |

The entire app is a single `index.html` file — no build step, no `node_modules`, no bundler.

---

## 📁 Project Structure

```
budget-planner/
└── index.html   # The entire app
└── README.md    # This file
```

---

## 🔒 Privacy

All your data stays in your browser. Nothing is sent to any server. The only external requests are to Google Fonts for typography — you can remove those too if you want to go fully offline by replacing the `<link>` tag with locally hosted fonts.

---

*A personal project by [keatyi](https://github.com/keatyi)*
