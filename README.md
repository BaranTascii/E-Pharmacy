# Admin Dashboard - Frontend Application

This repository contains the frontend application for the Admin Dashboard, designed to provide a comprehensive and intuitive interface for managing and visualizing data related to a medical store's operations. It consumes data from a separate backend API to display income, expenses, product information, customer details, and supplier data.

## Demo Credentials

To log in and explore the dashboard features, please use the following pre-configured admin vendor account:

* **Email Address:** `vendor@gmail.com`
* **Password:** `1234567`

---

## Features

The project consists of the following dedicated pages and modules:

* **Log in:** Allows authorized users to securely authenticate and access the dashboard using their credentials.
* **Dashboard:** Highlights high-level business metrics including total products, suppliers, customers, recent customer sign-ups, and a financial breakdown of income and expenses.
* **All Orders:** Displays an organized, filterable list of all orders processed within the medical store.
* **All Products:** Features a robust product management view with functionality to view the complete inventory, add new products, and edit existing product records.
* **All Suppliers:** Provides a dedicated vendor directory with complete capabilities to add new supplier profiles and update supplier contact/business details.
* **All Customers:** Displays a comprehensive list of registered customers for CRM and order tracking.

### Additional Highlights
* **Authentication Flow:** Complete user authorization support (secure session login and logout features).
* **Responsive Design:** Fully optimized layout adapting seamlessly across mobile, tablet, and desktop viewports.

## Technologies Used

* **React** — Component-based UI rendering
* **Redux** — Centralized client-side state management
* **React Router** — Declarative single-page application (SPA) routing
* **React Hook Form** — Performance-optimized, flexible form validation
* **MUI X** — Advanced UI components and data grids for data-heavy views
* **CSS Modules** — Locally-scoped component styling to prevent global leaks
* **Vite** — Next-generation ultra-fast frontend tooling and bundling
* **Axios** — Promise-based HTTP client for seamless backend API integration
* **REST API** — Architectural standard for data communication

## Installation and Startup

Follow these simple steps to spin up the project locally:

```bash
# 1. Clone the repository
git clone <repository-url>

# 2. Navigate to the project folder and install dependencies
npm install

# 3. Start the local development server
npm run dev