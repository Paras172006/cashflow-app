# 💰 CashFlow — MERN Full Stack Expense Tracker

A secure, full-stack personal finance application built with MongoDB, Express, React, and Node.js. CashFlow allows users to track expenses, visualize spending patterns through interactive charts, and manage their financial data — all behind a secure JWT-authenticated API.

## Features

- **User Authentication** — Secure sign up and login with JWT tokens
- **Password Security** — bcrypt hashing for safe password storage
- **Protected Routes** — Middleware-based route protection on both frontend and backend
- **Expense Management** — Full CRUD: create, read, update, and delete expenses
- **Category System** — 8 expense categories: Food & Dining, Transportation, Utilities, Entertainment, Healthcare, Shopping, Education, and Other
- **Advanced Filtering** — Filter expenses by category, date range, amount range, and search term
- **Dashboard Overview** — Stats cards, spending pie chart, trend line chart, and recent expenses
- **Analytics Dashboard** — Deep insights including yearly breakdowns, category comparisons, monthly overviews, and spending insights
- **Lazy Loading** — Year sections on the analytics page load on scroll via IntersectionObserver
- **Profile Management** — Update name, email, and password
- **Avatar Upload** — Upload, preview, and delete profile pictures (JPG/PNG, max 5MB)
- **Data Export** — Download all expenses and profile data as a JSON file
- **Account Deletion** — Permanently delete account and all associated data

## Technologies Used

### Frontend
- **React 19** — UI library
- **TypeScript** — Type safety
- **Vite** — Build tool and dev server
- **TanStack Router** — File-based routing with type safety
