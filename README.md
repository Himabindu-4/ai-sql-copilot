~~~ AI SQL Copilot
Ask Questions in Plain English. Get SQL, Charts, and Business Insights Instantly.
Transform natural language into SQL queries, execute them securely on PostgreSQL, visualize results, and generate AI-powered insights — all from a modern analytics dashboard.

Features:
1. Natural Language to SQL
   > Ask questions like:
   > Show total sales by customer
   > Revenue by region
   > Top selling products
   > Low stock products
   > Sales over time
   > Customer-wise order counts
2.Automatically generates optimized SQL queries.
3.Secure SQL Execution
   - Read-only query execution
   - Blocks dangerous SQL commands
   - Automatic result limiting
   - PostgreSQL integration
4.Interactive Data Visualization
5.Generate charts automatically from query results.
  Supported:
  - 📈 Line Charts
  - 📊 Bar Charts
  - 🥧 Pie Charts
  - 🔵 Scatter Plots
 Chart Builder:
 Customize visualizations:
 - Select chart type
 - Choose X-axis
 - Choose Y-axis
 - Instantly update charts

6.Editable SQL Workspace
  - View generated SQL
  - Edit queries manually
  - Re-run SQL instantly
  - Experiment like professional BI tools

7.AI Business Insights
Automatically generates narrative summaries such as:
* Revenue peaked at ₹151,200 in the South region.

* South contributes nearly 70% of total revenue,
  making it the strongest-performing region.

8.Query History
  Automatically saves recent queries.
  - Reopen previous analyses
  - Load SQL instantly
  - Persistent local storage

9.CSV Export
  Download query results with one click.
  Perfect for Excel and reporting workflows.

10.Dashboard Widgets
  Pin important analyses to your dashboard.
  Examples:
- Revenue Overview
- Top Customers
- Product Performance
- Inventory Monitoring

11.Query Sharing
  Generate shareable links for dashboards and analyses.

12.Workspace Mode
   Choose your role:
* Analyst Workspace has access to:
- SQL Editor
- Raw Data
- Charts
- Query Execution

* Executive Workspace has access to:
- Dashboards
- Charts
- Insights


System Architecture:
┌────────────────────┐
│ User Question      │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│ AI SQL Generator   │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│ PostgreSQL Engine  │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│ Query Results      │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│ Charts + Insights  │
└────────────────────┘

Tech Stack:
A. Frontend:
- Next.js 16
- React
- TypeScript
- Tailwind CSS
- Plotly.js

B. Backend
- Next.js API Routes
- PostgreSQL
- Node.js

C. Data Layer
- PostgreSQL
- pg Driver

D. Visualization
- React Plotly
- Dynamic Chart Builder

Clone Repository:

* https://github.com/Himabindu-4/ai-sql-copilot.git
Install Dependencies:
- npm install
  
Configure Environment:

- Start Development Server
  npm run dev  
- Open:
  http://localhost:3000

Example Queries:

> Sales Analytics

* Show total sales by customer
* Revenue by region
* Sales over time
  
> Customer Analytics:

* Customer-wise order counts
* Which customer spent the most?
  
> Product Analytics:

* Top selling products
* Best selling product
* Low stock products
  
> Order Analytics example:

* Count total orders
* Show average order amount
  
Security Features:

1. Blocks
   * DROP
   * DELETE
   * UPDATE
   * ALTER
   * TRUNCATE
   * INSERT

2.Read-only analytics
3.Safe query execution
4.Result limits

Future Enhancements:

- Team Collaboration
- Scheduled Reports
- Multi-Tenant Workspaces
- Natural Language Dashboard Creation
  
Project Highlights:

✔ Natural Language to SQL
✔ PostgreSQL Analytics Engine
✔ Interactive Visualizations
✔ AI Generated Insights
✔ Dashboard Widgets
✔ CSV Export
✔ Query History
✔ Role-Based Workspace
✔ Modern Enterprise UI

Author:
Hima bindu
AI SQL Copilot — Modern AI-Powered Business Intelligence Platform
Built with using Next.js, PostgreSQL, TypeScript, and AI.
