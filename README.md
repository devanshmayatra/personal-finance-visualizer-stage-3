# Personal Finance Tracker

<p align="center">
  <!-- Badges are pre-filled with your repo details -->
  <a href="https://github.com/devanshmayatra/personal-finance-visualizer-stage-3/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/devanshmayatra/personal-finance-visualizer-stage-3?style=for-the-badge" alt="License">
  </a>
  <a href="https://github.com/devanshmayatra/personal-finance-visualizer-stage-3/issues">
    <img src="https://img.shields.io/github/issues/devanshmayatra/personal-finance-visualizer-stage-3?style=for-the-badge" alt="Issues">
  </a>
  <a href="https://github.com/devanshmayatra/personal-finance-visualizer-stage-3/stargazers">
    <img src="https://img.shields.io/github/stars/devanshmayatra/personal-finance-visualizer-stage-3?style=for-the-badge" alt="Stars">
  </a>
</p>


<p align="center">
  A web application to visually track, manage, and analyze your personal income and expenses.
</p>


<br />

> [!WARNING]
> **This project is not password-protected.** It is designed for learning and demonstration purposes. Please do not enter real or sensitive personal financial data.

<br />

<!-- TODO: Add a link to your live demo if you have one -->
<p align="center">
  <a href="https://personal-finance-visualizer-stage-3-two.vercel.app/">
    <img src="https://img.shields.io/badge/View%20Live%20Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo">
  </a>
</p>

<br />

<!-- TODO: Add a high-quality screenshot or GIF of your application's dashboard
<p align="center">
  <img src="[LINK_TO_YOUR_SCREENSHOT_OR_GIF]" alt="Finance Tracker Dashboard" width="800"/>
</p>
 -->
---

## ✨ Key Features

*   **📊 Interactive Dashboard:** Get a quick overview of your financial health with insightful charts and summaries.
*   **💸 Transaction Logging:** Easily add, edit, and delete income and expense records.
*   **📈 Data Visualization:** Understand your spending habits with dynamic charts for expenses by category.
*   **🏷️ Category Management:** Organize your transactions with customizable categories.
*   **📱 Responsive Design:** Track your finances on any device, whether desktop or mobile.

---

## 🛠️ Tech Stack

This project is built with a modern, performant, and scalable tech stack.

| Category      | Technology                                    |
| :------------ | :-------------------------------------------- |
| **Framework** | [Next.js](https://nextjs.org/) 14 (App Router)  |
| **Language**  | [TypeScript](https://www.typescriptlang.org/) |
| **Styling**   | [Tailwind CSS](https://tailwindcss.com/)      |
| **UI Components**|[Shadcn UI](https://ui.shadcn.com/docs/components)|
| **Database**  |[MongoDB](https://www.mongodb.com/docs/)|
| **Deployment**| [Vercel](https://vercel.com/)                 |

---

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

*   Node.js (v18.0 or later)
*   A package manager like `npm`, `yarn`, or `pnpm`
*   <!-- TODO: Add any other prerequisites, like a database connection string -->

### Installation

1.  **Clone the Repository**
    ```sh
    git clone https://github.com/devanshmayatra/personal-finance-visualizer-stage-3.git
    cd personal-finance-visualizer-stage-3
    ```

2.  **Install Dependencies**
    ```sh
    npm install
    ```

3.  **Configure Environment Variables**
    Create a `.env.local` file in the root directory and add any necessary variables.
    ```env
    # Example for a database connection
    # DATABASE_URL="your_connection_string_here"
    ```

### Running the Application

Start the development server with:
```sh
npm run dev


Open http://localhost:3000 in your browser to see the application.

📁 Project Structure

Here is an overview of the project's directory structure:

Generated code
src/
├── app/                  # Next.js App Router: handles routing and pages.
│   ├── (pages)/          # Route group for main application views.
│   │   ├── all-transactions/
│   │   ├── budget/
│   │   ├── charts/
│   │   └── transactions/
│   ├── api/              # Backend API endpoints.
│   │   ├── budgets/
│   │   ├── spending/
│   │   └── transactions/
│   ├── globals.css       # Global styles.
│   ├── layout.tsx        # Root application layout.
│   └── page.tsx          # The homepage component.
├── components/           # Reusable React components.
│   └── ui/               # UI library components (e.g., shadcn/ui).
├── hooks/                # Custom React hooks.
│   └── use-mobile.ts     # Hook to detect mobile devices.
├── lib/                  # Core logic and utility functions.
│   ├── db.ts             # Database connection and setup.
│   └── utils.ts          # General helper functions.
├── models/               # Database schemas (Mongoose models).
│   ├── budget.model.ts
│   └── transaction.model.ts
└── types/                # TypeScript type definitions.
    ├── budget.ts
    ├── category_total.ts
    └── transaction.ts
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
IGNORE_WHEN_COPYING_END
☁️ Deployment

The easiest way to deploy this Next.js app is to use the Vercel Platform.

🗺️ Roadmap

The highest priority for future development is adding security and authentication.

User Authentication: Implement password-protected accounts.

Budgeting Goals: Allow users to set and track monthly budgets.

Data Export: Add functionality to export transactions to CSV.

See the open issues for a full list of proposed features and known issues.

🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn and create. Any contributions you make are greatly appreciated. Please fork the repository and create a pull request.

Distributed under the MIT License. See LICENSE.txt for more information.

📧 Contact

Devansh Mayatra - @devanshmayatra

Project Link: https://github.com/devanshmayatra/personal-finance-visualizer-stage-3
