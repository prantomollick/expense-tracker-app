# Expense Tracker App

A dynamic, Vue.js-based expense tracker application built with Vite. This mini project allows users to manage their finances by adding, viewing, filtering, and deleting transactions—all while persisting data locally using the browser's localStorage.

## Table of Contents

-   [Features](#features)
-   [Technologies Used](#technologies-used)
-   [Project Structure](#project-structure)
-   [Setup and Installation](#setup-and-installation)
-   [Usage](#usage)
-   [Deployment](#deployment)
-   [Contributing](#contributing)
-   [License](#license)
-   [Contact](#contact)

## Features

-   **Transaction Management:**

    -   Add new transactions with a title, amount, and type (Income/Expense).
    -   View all transactions in a clean, responsive table.
    -   Delete transactions with a simple click.

-   **Filtering:**

    -   Filter transactions to view all, only income, or only expenses.

-   **Dynamic Styling:**

    -   Income transactions are displayed in **green**.
    -   Expense transactions are displayed in **red**.
    -   Expenses equal to or above $500 are highlighted in **bold**.
    -   Transaction type is always shown in uppercase.

-   **Form Validation:**

    -   Ensures that the amount is greater than 0 and not a negative value.
    -   Displays validation messages for incorrect inputs.

-   **Data Persistence:**
    -   Transactions are stored in localStorage, ensuring data remains after page reloads.

## Technologies Used

-   **Vue.js:** Framework for building user interfaces.
-   **Vite:** Fast build tool for modern web projects.
-   **Bootstrap:** (Optional) Used for styling and responsive design.
-   **LocalStorage:** For persisting transaction data.

## Project Structure

expense-tracker-app/

```bash
.
├── README.md
├── index.html
├── jsconfig.json
├── package-lock.json
├── package.json
├── public
│   └── favicon.ico
├── src
│   ├── App.vue
│   ├── assets
│   │   └── main.css
│   ├── components
│   │   ├── AddTransaction.vue
│   │   └── TransactionList.vue
│   └── main.js
└── vite.config.js

4 directories, 12 files
```

_Note: The project structure must remain unchanged as per the assignment guidelines. Additional files can be added if necessary, but do not modify the existing folders and files._

## Setup and Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/prantomollick/expense-tracker-vue-app
    cd expense-tracker-vue-app
    ```

2. Install Dependencies:

```bash
    npm install
```

3. Run the Application:

```bash
    npm run dev
```

The app should now be running on `http://localhost:3000` or the port specified in your terminal.

4. Build for Production:

```bash
    npm run build
```

## Usage

-   Adding a Transaction:
    Use the form in AddTransaction.vue to enter a transaction title, amount, and select the type (Income/Expense). Upon clicking "Add," the transaction is saved to localStorage and displayed in the table.

-   Viewing Transactions:
    All transactions are listed in a table (implemented manually using Bootstrap table styles). If no transactions exist, a message stating "No transactions recorded yet." is displayed.

-   Filtering Transactions:
    Toggle between All, Income, and Expense transactions to easily view your data.

-   Deleting a Transaction:
    Each transaction has an associated delete button. Clicking it removes the transaction and updates localStorage.

## Deployment

-   Live Demo:
    A live demo of a similar project is available [here]().

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request. Please ensure that your contributions maintain the project structure and follow the established coding standards.

## License

This project is licensed under the MIT License.

## Contact

Pranto Mollick – prantomollick01@gmail.com
GitHub: [prantomollick](https://github.com/prantomollick)
