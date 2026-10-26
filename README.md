# Smart Expense Tracker

A responsive personal finance web application built with React.js to help users track expenses, manage budgets, monitor subscriptions, and understand their spending habits through interactive charts and financial summaries.

The application provides a centralized dashboard for managing personal finances, organizing transactions, and reviewing spending patterns through a simple interface.

## Live Demo

**Live Application**  
https://web-project-ochre-mu.vercel.app

**GitHub Repository**  
https://github.com/shayna-exe/Web-project

## Overview

Managing personal finances requires keeping track of daily expenses, recurring subscriptions, and monthly budgets. Smart Expense Tracker provides a single interface to organize financial information and review spending patterns.

The application uses interactive charts to present financial data in a visual format. Users can categorize expenses, review spending summaries, and monitor their budgets without relying on a separate spreadsheet.

The project focuses on responsive web design, reusable React components, client-side state management, and interactive data visualization.

## Features

### Expense Management
- Record and organize personal expenses.
- Categorize transactions for easier tracking.
- Review spending patterns across expense categories.
- Maintain financial records within the application.

### Budget Management
- Set and monitor spending budgets.
- Compare expenses against budget limits.
- Review spending summaries to understand financial activity.

### Subscription Tracking
- Keep track of recurring subscriptions.
- Organize subscription-related expenses.
- Monitor recurring costs as part of overall spending.

### Financial Analytics
- Visualize expense distribution using interactive charts.
- Review category-wise spending through graphical summaries.
- Use bar charts and pie charts to understand spending patterns.
- Present financial information in a dashboard format.

### Data Management
- Store supported application data in browser localStorage.
- Retain locally stored information across browser sessions.
- Manage application state using React Hooks.

### User Interface
- Responsive layout for different screen sizes.
- Reusable components for a consistent interface.
- Navigation between application sections using React Router.
- Dark mode support.
- Interactive notifications for relevant user actions.

## Technology Stack

| Technology | Purpose |
|---|---|
| React.js | Building the user interface |
| JavaScript | Application logic and interactions |
| React Router | Client-side navigation |
| React Hooks | Managing component state and application behavior |
| Chart.js | Creating interactive charts |
| React Chart.js 2 | Integrating Chart.js with React |
| Recharts | Data visualization |
| React Icons | Interface icons |
| React Toastify | Toast notifications |
| HTML5 | Structuring the application |
| CSS3 | Styling and responsive layouts |
| localStorage | Client-side data persistence |
| Git and GitHub | Version control and source code management |
| Vercel | Hosting and deployment |

## Project Structure

The project follows a React application structure.

```text
Web-project/
├── public/
│   └── Static assets and public files
├── src/
│   ├── Components and application pages
│   ├── Styling files
│   ├── Application logic
│   └── React entry points
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

The exact contents of the `src` directory may vary depending on the current implementation.

## Getting Started

Follow these steps to run the project locally.

### Prerequisites

Install the following tools before proceeding.

- Node.js
- npm
- Git

You can download Node.js from https://nodejs.org/.

Verify that Node.js and npm are installed by running

```bash
node --version
npm --version
```

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/shayna-exe/Web-project.git
```

**2. Navigate to the project directory**

```bash
cd Web-project
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm start
```

**5. Open the application**

Visit the following address in your browser.

```text
http://localhost:3000
```

The application will run locally. Changes made to the source files will be reflected during development.

## Available Scripts

The project supports the following npm scripts.

| Command | Description |
|---|---|
| `npm start` | Starts the development server |
| `npm test` | Runs the configured test runner |
| `npm run build` | Creates an optimized production build |
| `npm run eject` | Exposes the underlying Create React App configuration |

**Note**  
The `npm run eject` command is irreversible. It is not required for normal development.

## Data Storage

The application uses browser localStorage for client-side data persistence.

This allows supported data to remain available when the user closes and reopens the browser.

Since localStorage is associated with a particular browser and origin, data is not automatically synchronized across different devices or browsers.

The project does not require a centralized database for its local storage functionality. Data synchronization between users or devices would require additional infrastructure.

## Deployment

The application is deployed using Vercel.

**Live URL**  
https://web-project-ochre-mu.vercel.app

To deploy your own instance

1. Push the project to a GitHub repository.
2. Import the repository into Vercel.
3. Configure the project using the appropriate Create React App build settings.
4. Set the build command to `npm run build`.
5. Set the output directory to `build`.
6. Deploy the application.

For an existing Vercel deployment connected to GitHub, subsequent pushes to the configured production branch can trigger new deployments automatically.

## Future Improvements

Potential improvements include

- Cloud-based storage and cross-device synchronization.
- User authentication and individual financial profiles.
- Exporting expense reports to CSV or PDF.
- Advanced monthly and yearly financial reports.
- Notifications for approaching budget limits.
- Improved recurring payment management.
- Additional filters for dates, categories, and transaction types.

These are possible extensions rather than a claim that they are already implemented.

## Learning Outcomes

This project provides practical experience with

- Building interactive web applications using React.js.
- Creating reusable components and managing application state.
- Implementing client-side routing.
- Visualizing financial data with charting libraries.
- Persisting application data using localStorage.
- Designing responsive user interfaces.
- Managing source code with Git and GitHub.
- Deploying a frontend application using Vercel.

## Author

**Shayna Datta**

GitHub Profile  
https://github.com/shayna-exe

## License

This project is available for educational and portfolio purposes. No specific open-source license is declared in this README. Add a license file to the repository if you intend to distribute the project under a particular license.
