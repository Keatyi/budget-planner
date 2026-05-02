# 🦋 My Budget Planner

A clean, minimal monthly budget planner that runs entirely in the browser — no accounts, no servers, no subscriptions.

🔗 **Live link: [keatyi.github.io/budget-planner](https://keatyi.github.io/budget-planner/)**

---

## ✨ Features

### 📅 Planner

**Income Tracking**
- Add **multiple income sources** (salary, part-time job, freelance, etc.)
- **Rename** any income source by clicking the ✎ pencil icon
- **Remove** extra sources with the ✕ button
- Live **Total** updates as you type

**Budget Categories**
- Default categories: **Needs, Savings, Wants, Entertainment**
- Fully customisable - **Add, rename, recolour, or remove** categories via the Edit Categories modal
- Percentage split always kept visible so you can balance your budget at a glance
- Each category shows budget allocation, amount spent, and remaining balance

**Monthly Breakdown**
- Switch between any month of the year using the month bar
- Each category expands into individual expense line items
- **Add or remove** expense items freely
- Track individual expenses within each category with live progress bars showing spending vs. budget
- Over-budget items highlighted in red
- Add a monthly note for context (e.g. Raya spending, bought a laptop)

---

### 💰 Savings

- Add **savings goals** with a custom name, yearly target amount, and a link to a specific line item in the Planner (e.g. "Emergency Fund")
- Each goal card shows: **Target / Saved / Remaining / Progress %** with a progress bar
- Progress updates **automatically** as you log savings amounts in the Planner — no manual input needed on the Savings page
- Goals are **editable and deletable** at any time
- 🎉 Completion state shown when a goal is reached, including surplus amount

---

### 📊 Year Summary

- A full **Jan–Dec table** showing all categories and line items side by side
- Income totals (combined across all sources) shown per month
- Only months with data are shown
- Cumulative totals per expense item
- Current month is highlighted for easy reference
- Print the full year summary as a clean PDF

---

## 🛠️ Utilities

### 💾 Data Persistence
- Everything saves automatically to **localStorage** — no manual saving needed
- A subtle dot indicator confirms when data is saved
- Export to PDF as a backup in case your browser cache is cleared

### ↩ Copy last month
- Carry over last month's income and amounts as a starting point

### ✕ Clear amounts
- Zero out all income and expenses for the current month while keeping your labels

### 📄 Save as PDF
- Export the current month's planner, savings or the year summary as a clean PDF
- The PDF is designed to fit cleanly on a single A4 page.

### 🌙 Dark Mode
- Toggle between light and dark themes
- Preference is saved automatically

---

## 🚀 Getting Started

No installation needed.

1. Download `index.html`
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. Start entering your income and expenses

That's it.

---

## 🗃️ Data & Privacy

All data is stored in your browser's `localStorage` — it never leaves your device. Clearing browser data will erase your budget history, so use the **Save as PDF** feature to keep permanent records.

---

## 🛠️ Tech Stack

| | |
|---|---|
| **HTML / CSS / JS** | Single self-contained file, zero dependencies |
| **Fonts** | Shippori Mincho + DM Sans via Google Fonts |
| **Storage** | Browser `localStorage` |
| **Compatibility** | All modern browsers (Chrome, Firefox, Safari, Edge) |

---

## 📁 Project Structure

```
budget-planner/
└── index.html   # The entire app
└── README.md    
```

---

*A personal project by [keatyi](https://github.com/keatyi)*
