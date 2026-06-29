# Nakwa Enterprises — Inventory Management System

A lightweight, offline-compatible inventory dashboard built for internal use across Nakwa Enterprises branches. No server, no database — runs entirely in the browser from a single HTML file.

---

## Features

- **Branch Views** — Switch between Shivamogga and Bhadravati branch inventories
- **Stock Tracking** — View current stock levels with cost price and selling price per item
- **Margin Display** — Automatically calculates and displays profit margin for each product
- **Restock Alerts** — Highlights items that have fallen below the minimum stock threshold
- **Bulk Stock Updates** — Update multiple item quantities at once
- **Supplier Contacts** — Quick-access directory of supplier details per product category
- **Category-wise Reporting** — Filter and view inventory by product category
- **Excel Export** — Export current inventory data to `.xlsx` for records or sharing

---

## Product Categories

- Fishnets
- Tarpaulins
- Ropes
- Shade Nets
- Agricultural Items
- Household Goods

---

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge)
2. Select your branch from the top navigation (Shivamogga / Bhadravati)
3. Browse inventory by category or search for a specific item
4. Use the **Update Stock** button to edit quantities
5. Click **Export** to download the current view as an Excel file

> No internet connection required. All data is stored locally in the browser.

---

## File Structure

```
nakwa-inventory/
│
├── index.html          # Main application file (entire app lives here)
└── README.md           # This file
```

---

## Tech Stack

| Layer      | Technology              |
|------------|-------------------------|
| Structure  | HTML5                   |
| Styling    | CSS3                    |
| Logic      | Vanilla JavaScript      |
| Export     | SheetJS (xlsx library)  |
| Storage    | Browser LocalStorage    |

---

## Branches

| Branch      | Location         |
|-------------|------------------|
| Shivamogga  | Main branch      |
| Bhadravati  | Secondary branch |

---

## Notes

- Data persists in the browser's local storage — clearing browser data will reset the inventory
- For a shared/synced version across branches, a backend or cloud database would need to be added
- The Excel export is useful for monthly stock audits or sharing updates with the head office

---

## Maintained By

**Nakwa Enterprises
