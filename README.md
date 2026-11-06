# Inventory Management System

**Course:** Web Programming  
**Task:** Task 2 — Building the User Interface Using HTML and CSS  
**Phase:** Phase 2: HTML and CSS Implementation  
**Project:** Inventory Management System (approved group concept note)

## Overview
Inventory Management System is a front-end interface for small businesses, campus enterprises and local retail stores. It demonstrates navigation, stock overviews, forms, categories, suppliers and reports.

**Important:** This submission uses **HTML and CSS only**. It does **not** include JavaScript, PHP or MySQL. All records, reports, charts and statistics are sample data. Forms, search controls and delete confirmation do not process or save data. These features are reserved for later phases.

## How to open
1. Download/extract the repository folder.
2. Open `index.html` in any modern web browser.
3. Follow the sidebar navigation links to all other pages.
4. Optional: open `login.html` to preview the login screen and navigate to the dashboard.

No installation, server, database or software packages are required. Google Fonts are optional; system fonts are used if offline.

## Project pages

| File | Purpose |
|---|---|
| `index.html` | Home dashboard with summary cards and sample stock overview |
| `inventory.html` | Inventory table, sample records and search/filter UI |
| `add-item.html` | New inventory item form |
| `edit-item.html` | Example pre-filled edit item form |
| `item-details.html` | View a product record |
| `delete-item.html` | Example delete confirmation screen (non-functional) |
| `categories.html` | Categories list and entry form |
| `suppliers.html` | Suppliers directory and entry form |
| `reports.html` | Stock summaries and CSS chart |
| `about.html` | Project background, objectives and group |
| `login.html` | Optional static demonstration login interface |

## Structure
```
inventory-management-system/
├── index.html
├── inventory.html
├── add-item.html
├── edit-item.html
├── item-details.html
├── delete-item.html
├── categories.html
├── suppliers.html
├── reports.html
├── about.html
├── login.html
├── README.md
└── assets/
    ├── css/style.css
    └── img/logo.svg
```

## Group members
1. Chawanangwa Mhlanga — CEN 01/42/24
2. Anderson Monjeza — CEN 01/57/24
3. Albert Goodwin — CEN 01/56/24
4. Peace Ziwawo — ICT 01/14/24
5. Brighton Katangala — CEN 01/01/24
6. Thomas Nedi — CEN 01/17/20


### Fair division of work
- Chawanangwa: dashboard and navigation
- Anderson: inventory list and sample records
- Albert: add/edit/view/delete screens
- Peace: categories and suppliers
- Brighton: reports and responsive CSS
- Thomas: README, cross-page testing and accessibility



## Interface layout
The blue top navigation, dark left sidebar, and coloured summary cards follow the supplied reference screenshot. All pages use the same stylesheet.

## Icon and mobile layout
All interface icons are local SVG files in `assets/icons/`. No external icon service is required. The sidebar switches to a horizontally scrollable navigation bar on small screens. Wide tables scroll horizontally to keep all data accessible.
