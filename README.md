# Gift Basket E-Commerce Database

Database Systems course project, Ben-Gurion University, 2025. Team project (3 students).

An end-to-end database project for **Build Your Basket**, a real US company that sells customizable gift baskets online: from analyzing the business and its website, through conceptual and relational design, to generating data and building management reports.

## What we did
1. **Business analysis:** studied the company's website and operations and identified its main challenges, such as seasonal demand and keeping online inventory in sync with physical stock.
2. **Conceptual design:** built an entity-relationship (ERD) model of customers, baskets, products, packages, carts, orders, payments, greetings and subscriptions, then revised it based on reviewer feedback (for example, separating basket types from customer-specific basket versions, and allowing the same product more than once in a basket).
3. **Relational design:** translated the ERD into a normalized relational schema.
4. **Data generation:** produced synthetic data for 11 tables (orders, carts, payments, products, greetings, packages and more) with Excel formulas.
5. **Analytics:** wrote SQL views (KPIs, actual vs. targets, best and worst countries, top and least active customers, revenue by package) and built Power BI reports on top of them.

## Contents
| Folder | What's inside |
|---|---|
| `reports/` | Part A (requirements and ERD) and Part B (data model and database), in Hebrew |
| `data/` | Synthetic data generation workbook |
| `power-bi/` | Management dashboard and marketing report (open with Power BI Desktop) |

All customer, order and payment data in this project is synthetic and randomly generated.
