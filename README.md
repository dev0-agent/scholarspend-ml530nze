# ScholarSpend 🎓

> The privacy-first budget tracker for students.

ScholarSpend is a lightweight, offline-first financial tracker designed to help students manage their budget without complex accounting software or bank integrations. All data stays in your browser.

## Tech Stack

*   **Framework:** React 18
*   **Build Tool:** Vite
*   **Styling:** Tailwind CSS
*   **Icons:** Lucide React
*   **Charts:** Recharts
*   **State/Persistence:** React Context + LocalStorage

## Features

*   **💸 Instant Logging:** Quickly add expenses and income on the go.
*   **🔒 Private:** No servers, no tracking. Data lives in your browser's LocalStorage.
*   **📊 Visual Insights:** See exactly where your money goes with dynamic charts.
*   **📂 Data Portability:** Export your financial data to JSON for backups.
*   **📱 Mobile Ready:** Fully responsive design for tracking expenses between classes.

## Getting Started

1.  **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/scholarspend.git
    cd scholarspend
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    ```

## Project Structure

*   `src/components`: UI components (Forms, Charts, Lists)
*   `src/context`: Global state management
*   `src/hooks`: Custom hooks (useLocalStorage)
*   `src/utils`: Helper functions (Currency formatting, Date parsing)

## Documentation

*   [Task List](./TASKLIST.md)
*   [Learnings](./LEARNINGS.md)
*   [Development Rules](./.dev0/RULES.md)