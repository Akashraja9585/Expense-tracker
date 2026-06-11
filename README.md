# Expense Tracker 📊

A personal finance tracker where you can log your income and expenses, see your current balance, and visualize your spending by category. Built this to get hands-on with React state management and data visualization.

## What it does

- Add income and expense entries with a name, amount, and category
- Instantly updates total balance, total income, and total expenses
- Pie chart showing spending breakdown by category
- Delete any entry
- Data stays saved even after refreshing the page

## Tech used

- React.js
- Chart.js (for pie/bar charts)
- LocalStorage (for saving data)
- Tailwind CSS (for styling)

## Getting started

Clone the repo and install dependencies:

```bash
git clone https://github.com/Akashraja9585/expense-tracker.git
cd expense-tracker
npm install
npm start
```

No API key needed — works fully offline.

## Folder structure
src/
├── components/
│   ├── AddTransaction.jsx
│   ├── TransactionList.jsx
│   ├── Balance.jsx
│   └── ExpenseChart.jsx
├── App.jsx
└── index.js

## What I learned

Managing state across multiple components was the biggest challenge here. Understanding how to lift state up to a parent component and pass it down as props made things click for me.

Also learned how LocalStorage works — it was satisfying to refresh the page and see the data still there without any backend.

Chart.js was surprisingly easy to integrate once I understood the data format it expects.

## Future improvements

- Add monthly view to track spending over time
- Set budget limits per category with alerts
- Export data as CSV
- Add user authentication

## License

MIT
