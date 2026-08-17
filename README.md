# Snackulator 🍽️

> A simple, privacy-focused nutrition tracker that keeps your food data local.

Snackulator is a lightweight, browser-based nutrition and calorie tracking application designed to make daily food logging simple and straightforward.

It runs directly from a single HTML file and does not require an account, backend, or database server. Your nutrition data is stored locally in your browser.

---

## ✨ Features

### 📊 Nutrition Dashboard

Track your daily:

- Calories
- Protein
- Carbohydrates
- Fat
- Fiber
- Water intake

The dashboard provides a quick overview of your progress toward your daily nutrition targets.

### 🍎 Food Logger

Log foods you've added to your personal library and specify how much you consumed.

Snackulator automatically calculates the corresponding:

- Calories
- Protein
- Carbohydrates
- Fat
- Fiber

based on the quantity consumed.

Foods can be assigned to different meal categories such as:

- Breakfast
- Lunch
- Dinner
- Snack
- Miscellaneous

### 📚 Personal Food Library

Create and manage your own collection of foods.

Each food can contain:

- Food name
- Serving unit
- Calories
- Protein
- Carbohydrates
- Fat
- Fiber

The library also includes a search function to quickly find foods.

### 💧 Water Tracking

Track daily water intake and compare it against your personal hydration target.

### 📅 History & Activity

Review previously logged meals, nutrition totals, water intake, and activity over time.

### 🎯 Custom Nutrition Targets

Set your own daily targets for:

- Calories
- Protein
- Carbohydrates
- Fat
- Fiber
- Water

### 💾 Local Data Storage

Snackulator stores application data locally in your browser.

No account or cloud database is required.

### 📤 Data Export & Import

Export your data for backup and restore it later if needed.

Supported export formats include:

- JSON backup
- CSV nutrition ledger

---

## 🔐 Privacy

Snackulator is designed around a local-first approach.

Your food logs, food library, targets, and other application data are stored in your browser's local storage.

There is no Snackulator account system or application backend.

> Your data stays in the browser where you use the application.

Because the application relies on browser storage, clearing the site's local storage or browser data can remove your saved information.

**Always keep an exported backup if your data is important.**

---

## 🚀 Getting Started

Snackulator does not require a build process.

### Option 1 — Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Start adding foods and logging meals.

### Option 2 — Use GitHub Pages

The project can also be hosted as a static website because the application does not require a backend server.

---

## 🛠️ Technology

Snackulator is intentionally lightweight.

### Frontend

- HTML5
- CSS3
- JavaScript
- Browser Local Storage

### Data Visualization

- Chart.js

The application is contained primarily within a single `index.html` file.

---

## 📁 Project Structure

```text
Snackulator/
│
├── index.html      # Main application
├── README.md       # Project documentation
└── .gitignore      # Git configuration (if present)
