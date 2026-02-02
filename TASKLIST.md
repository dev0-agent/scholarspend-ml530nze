# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Project Initialization & Tooling**
  Initialize a new Vite + React project. Configure Tailwind CSS for styling. Set up the folder structure (components, hooks, context, utils). Install necessary dependencies (lucide-react, recharts, clsx). verify the app runs locally.

- [ ] ⏳ **Implement Storage Hook & Context**
  Create a robust `useLocalStorage` hook that handles JSON serialization/deserialization safely. Create a `FinanceContext` that provides the global state (transactions array, currency settings) and methods (addTransaction, deleteTransaction) to the app. Ensure data persists on page reload.

## Phase 2

- [ ] ⏳ **Create Transaction Form Component**
  Build a form component to add new transactions. Fields: Title, Amount, Type (Income/Expense), Category, and Date. Include validation (amount must be positive, title required). On submit, it should update the global context.

- [ ] ⏳ **Build Recent Transactions List**
  Create a component to display the list of transactions. Group them by date (e.g., 'Today', 'Yesterday'). Include a delete button for each item. Use Lucide icons to represent categories visually. Ensure the list updates immediately when a new transaction is added.

- [ ] ⏳ **Develop Dashboard Summary Cards**
  Create summary cards at the top of the UI showing: Total Balance, Total Income, and Total Expenses. These should be calculated dynamically from the transaction list in the Context.

## Phase 3

- [ ] ⏳ **Implement Spending Visualization**
  Integrate `recharts` to display a Donut Chart showing expenses by category. It should only calculate based on 'Expense' type transactions. Handle the empty state (no data) gracefully.

- [ ] ⏳ **Add Category Management**
  Allow users to define custom categories or select from a default student-focused list (Food, Transport, Books, Party). Store these preferences in LocalStorage alongside transactions.

- [ ] ⏳ **Data Export/Import Feature**
  Add a Settings area with buttons to 'Export Data' (downloads a JSON file) and 'Import Data' (reads a JSON file and replaces current state). Include basic validation to prevent importing invalid JSON structures.

## Phase 4

- [ ] ⏳ **UI Polish & Responsive Design**
  Refine the styling using Tailwind. Ensure the layout works perfectly on mobile (stacking order) and desktop. Add hover states, transitions, and empty state illustrations when no transactions exist.

## Phase 5

- [ ] ⏳ **Final Testing & Documentation**
  Perform a manual test pass of all flows (Add, Delete, Import, Persist). Fix any z-index or overflow bugs. Ensure the README is up to date with screenshots (placeholders) and deployment instructions.

---

_Last updated by dev0 automation_
