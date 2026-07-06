# 🚀 AI SQL Copilot

**AI SQL Copilot** is an AI-powered Business Intelligence platform that transforms **natural language questions into SQL queries**, executes them securely on **PostgreSQL**, visualizes the results with interactive charts, and generates meaningful business insights—all from a modern analytics dashboard.

Designed for analysts, managers, and business users, the platform makes data exploration simple without requiring SQL expertise.

---

# ✨ Features

## 🤖 Natural Language to SQL

Ask questions in plain English, such as:

* Show total sales by customer
* Revenue by region
* Top selling products
* Low stock products
* Sales over time
* Customer-wise order counts
* Which customer spent the most?

The AI automatically generates optimized SQL queries for PostgreSQL.

---

## 🔒 Secure SQL Execution

Security is built into the query engine.

* Read-only query execution
* Blocks dangerous SQL statements
* Automatic result limiting
* PostgreSQL integration

Blocked SQL commands include:

* DROP
* DELETE
* UPDATE
* INSERT
* ALTER
* TRUNCATE

---

## 📊 Interactive Data Visualization

Automatically visualize query results using interactive charts.

Supported chart types:

* 📈 Line Chart
* 📊 Bar Chart
* 🥧 Pie Chart
* 🔵 Scatter Plot

### Chart Builder

Customize visualizations by selecting:

* Chart type
* X-axis
* Y-axis

Charts update instantly based on your selections.

---

## 💻 Editable SQL Workspace

Power users can inspect and modify generated SQL.

Features include:

* View AI-generated SQL
* Edit queries manually
* Execute modified queries
* Experiment like professional BI tools

---

## 🧠 AI Business Insights

Automatically generate human-readable summaries from query results.

Example insights:

> Revenue peaked at ₹151,200 in the South region.

> South contributes nearly 70% of total revenue, making it the strongest-performing region.

---

## 🕒 Query History

Never lose previous analyses.

* Automatically saves recent queries
* Reload previous SQL instantly
* Persistent local storage

---

## 📄 CSV Export

Export query results with a single click.

Perfect for:

* Excel
* Reports
* Data sharing

---

## 📌 Dashboard Widgets

Pin frequently used analyses to your dashboard.

Examples:

* Revenue Overview
* Top Customers
* Product Performance
* Inventory Monitoring

---

## 🔗 Query Sharing

Generate shareable links for dashboards and saved analyses.

---

## 👥 Workspace Modes

### Analyst Workspace

Includes:

* SQL Editor
* Raw Data
* Query Execution
* Interactive Charts

### Executive Workspace

Focused on business users with:

* Dashboards
* Charts
* AI Insights

---

# 🏗️ System Architecture

```text
User Question
       │
       ▼
AI SQL Generator
       │
       ▼
PostgreSQL Database
       │
       ▼
Query Results
       │
       ▼
Charts + AI Business Insights
```

---

# 🛠️ Tech Stack

## Frontend

* Next.js 16
* React
* TypeScript
* Tailwind CSS
* Plotly.js

## Backend

* Next.js API Routes
* Node.js

## Database

* PostgreSQL
* pg Driver

## Visualization

* React Plotly
* Dynamic Chart Builder

---

# 📂 Installation

Clone the repository:

```bash
git clone https://github.com/Himabindu-4/ai-sql-copilot.git
```

Move into the project directory:

```bash
cd ai-sql-copilot
```

Install dependencies:

```bash
npm install
```

Configure your environment variables.

Start the development server:

```bash
npm run dev
```

Open your browser:

```text
http://localhost:3000
```

---

# 💡 Example Queries

## Sales Analytics

* Show total sales by customer
* Revenue by region
* Sales over time

## Customer Analytics

* Customer-wise order counts
* Which customer spent the most?

## Product Analytics

* Top selling products
* Best selling product
* Low stock products

## Order Analytics

* Count total orders
* Show average order amount

---

# 🔐 Security

The application is designed for analytics workloads only.

✅ Read-only SQL execution

✅ SQL validation

✅ Dangerous commands blocked

✅ Automatic result limiting

---

# 🚀 Future Enhancements

* Team Collaboration
* Scheduled Reports
* Multi-Tenant Workspaces
* AI Dashboard Generation
* Saved Dashboard Templates
* User Authentication & Authorization
* Database Connection Manager
* Support for MySQL, SQL Server, and SQLite

---

# 📸 Screenshots

Add screenshots here to showcase:

* Dashboard
* SQL Editor
* Charts
* AI Insights
* Workspace Modes

---

# 🌟 Project Highlights

* 🤖 Natural Language → SQL
* 📊 Interactive Visualizations
* 🧠 AI-Generated Business Insights
* 🔒 Secure Read-Only Query Execution
* 📌 Dashboard Widgets
* 📄 CSV Export
* 🕒 Query History
* 👥 Role-Based Workspaces
* ⚡ Modern Enterprise UI
* 🐘 PostgreSQL Analytics

---

# 👩‍💻 Author

**Hima Bindu**

AI SQL Copilot — A modern AI-powered Business Intelligence platform built with **Next.js**, **TypeScript**, **PostgreSQL**, **React**, and **AI**.
