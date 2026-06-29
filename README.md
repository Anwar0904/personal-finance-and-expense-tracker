# Personal Finance & Expense Tracker (PFET)

Personal Finance & Expense Tracker (PFET) is a modern, responsive web application designed to help users seamlessly record income and expenses, manage budgets, visualize spending trends, and take control of their financial health through insightful analytics.

---

## The Problem & Our Solution

### The Problem
Staying on top of personal finances is a universal challenge. Many people:
*   **Lose track** of daily and monthly spending.
*   **Struggle to maintain** or stick to realistic budgets.
*   **Lack visual clarity** regarding where their money is actually going.

### Our Solution
PFET bridges this gap by providing an intuitive, centralized dashboard that transforms raw financial data into clear, actionable visual insights, empowering users to make smarter financial decisions.

---

## Target Users
PFET is built for **anyone looking to improve their money management habits**—from students tracking a tight budget to professionals managing multiple income streams and investments.

---

## Feature Roadmap & Requirements

### MVP Scope (Core Features)

#### 1. Authentication & Profile
Secure user onboarding and account management:
*   Register, Login, & Logout
*   Forgot / Reset / Change Password
*   Email Verification
*   Update Profile & Delete Account

#### 2. Comprehensive Dashboard
A centralized hub providing an at-a-glance summary of your financial status:
*   **Metrics:** Total Balance, Monthly Income, Monthly Expense, and Savings.
*   **Visuals:** Recent Transactions, Monthly Chart, Budget Status, and Expense Categories breakdown.

#### 3. Transaction Management (CRUD)
*   **Expenses:** Track via Title, Amount, Category, Date, Payment Method, Notes, Receipt Image, Tags, and Recurring status.
*   **Income:** Track via Title, Amount, Source, Date, and Notes.

#### 4. Categories & Budgets
*   **Pre-defined Categories:** Food, Shopping, Education, Salary, Entertainment, Bills, Fuel, Investment.
*   **Custom Categories:** Users can create, update, and manage their own categories.
*   **Budgets:** Set and track strict Monthly Budgets.

#### 5. Search, Filters, & Analytics
*   **Search:** Quick search by Title, Category, Date, or Amount.
*   **Filters:** Narrow down data by Category, Date Range, Payment Method, or Transaction Type (Income/Expense).
*   **Visual Charts:** Interactive Pie, Bar, Line, and Area charts.

---

### Advanced Features (Post-MVP)

*   **Smart Tools:** Receipt OCR (Optical Character Recognition) for automatic expense logging.
*   **Insights:** AI-powered spending insights and personalized financial advice.
*   **Multi-Account:** Support for multiple wallets, bank accounts, or currency conversions.
*   **Automation:** Recurring transaction reminders and notifications.
*   **Enhanced Reporting:** Advanced data exports (CSV, PDF) filtered by Week, Month, Year, Category, or Income vs. Expense.
*   **UI/UX:** Customizable Dark Mode.

---

## Non-Functional Requirements

### ⚡ Performance & Quality
*   **Speed:** Fast page loads utilizing optimized images and code splitting/lazy loading where appropriate.
*   **Codebase:** Strongly typed with **TypeScript**, enforced by **ESLint** and **Prettier** formatting guidelines.
*   **Workflows:** Meaningful semantic commit messages and clean, reusable component architecture.

### Security & Accessibility
*   **Security:** Robust password hashing, strict input validation, multi-layer authorization, and API rate limiting.
*   **Accessibility (a11y):** Full keyboard navigation support, semantic HTML with ARIA labels, and WCAG-compliant color contrast.
*   **Responsive UI:** Seamless experience optimized across Mobile, Tablet, and Desktop displays.

---

## 🛠️ Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/pfet.git](https://github.com/your-username/pfet.git)
   cd pfet