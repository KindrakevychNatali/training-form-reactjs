
# React Form Training Project

### Overview

This project is a React-based application that includes form handling using Formik and Yup for validation. It also includes testing utilities for React components.

### Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Available Scripts](#available-scripts)
- [Dependencies](#dependencies)
- [DevDependencies](#devdependencies)
- [Project Structure](#project-structure)
- [License](#license)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/KindrakevychNatali/training-form-reactjs.git
   cd react-form-project
   ```

2. **Install the dependencies:**

   ```sh
   npm install
   ```

### Usage

To start the development server, run:

```sh
npm start
```

This will start the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Available Scripts

In the project directory, you can run:

- **`npm start`**: Runs the app in the development mode.
- **`npm build`**: Builds the app for production to the `build` folder.
- **`npm test`**: Launches the test runner in the interactive watch mode.
- **`npm eject`**: Ejects the app from `react-scripts` and configures all build settings manually.

### Dependencies

- **`@testing-library/jest-dom`**: ^5.11.4
- **`@testing-library/react`**: ^11.1.0
- **`@testing-library/user-event`**: ^12.1.10
- **`formik`**: ^2.4.2
- **`react`**: ^17.0.2
- **`react-dom`**: ^17.0.2
- **`react-scripts`**: 4.0.3
- **`web-vitals`**: ^1.0.1
- **`yup`**: ^1.2.0

### DevDependencies

- **`sass`**: ^1.42.1

### Project Structure

```
├── public
│   ├── index.html
│   └── ...
├── src
│   ├── App.js
│   ├── Form.js
│   ├── Formik.js
│   ├── index.js
│   ├── Form-yup_validation.js
│   │   └── ...
├── .gitignore
├── package.json
├── README.md
└── ...
```
### Project Structure

```
├── public
│   ├── index.html
│   └── ...
├── src
│   ├── components
│   │   ├── AddBudgetModal.js
│   │   ├── AddExpenseModal.js
│   │   ├── BudgetCard.js
│   │   ├── Calculator.js
│   │   ├── TotalBudgetCard.js
│   │   ├── UncategorizedBudgetCard.js
│   │   ├── ViewExpensesModal.js
│   │   └── ...
│   ├── contexts
│   │   ├── BudgetsContext.js
│   │   └── ...
│   ├── styles
│   │   ├── Calculator.css
│   │   └── ...
│   ├── App.js
│   ├── index.js
│   └── ...
├── .gitignore
├── package.json
├── README.md
└── ...
```

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Additional Notes

- **Formik** and **Yup** are used for form handling and validation.
- **React Testing Library** is included for writing tests.
- **Sass** is used for styling, which allows for more advanced CSS features.

This README file provides a basic overview of the project and its structure, helping new contributors to get started quickly.
