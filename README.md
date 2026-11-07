# Income Sources Dashboard (Excel)

An interactive Excel dashboard that breaks total income down by **product** and **payment method**, compares **B2B vs B2C** sales, and tracks **actual income against target**, with a year selector (2023 / 2024 / 2025).

![Dashboard overview](images//blob/main/Screenshot%202026-11-07%20204836.png)

## What it shows

- **Income achieved vs target** for the selected year (percentage in the center ring)
- **Income by product** (Chair, Desk, Laptop, Monitor, Phone, Printer, Tablet), with the top source highlighted
- **Payment-method breakdown per product** (Cash, Online, Credit Card, Debit Card, Gift Card), shown as branches around each product
- **B2B vs B2C split** (Wholesale = B2B, Retail = B2C)
- **Average monthly income**, **monthly trend**, and **operating profit** by month
- **Quantity sold per item**

## Built with

- Microsoft Excel: PivotTables, slicers, formulas, charts
- Shapes and text boxes linked to PivotTable cells for dynamic labels
- Dataset: transactional sales data (orders, products, regions, customer type, payment method, discounts, shipping cost, income)

## Data and checks

The dashboard is driven by a sales table with columns such as `Year`, `Region`, `Product`, `Quantity`, `UnitPrice`, `CustomerType`, `PaymentMethod`, `TotalPrice`, `ShippingCost`, `Income`.

Reconciliation checks I applied:

- The payment-method branches of each product sum to that product's total
- The product totals sum to total income achieved
- B2B + B2C equals total income achieved
- Average monthly income = total income / 12

*(Edit the list above to match exactly what you added yourself.)*

## How to use

1. Download `Income_Sources_Dashboard.xlsx`
2. Open in Excel 2016 or later (Microsoft 365 recommended)
3. Use the year selector to switch between 2023, 2024 and 2025

## About me

Alireza Shiri, accounting and financial analysis. Interested in reconciliation, financial reporting and data analytics (Excel, Power BI, SQL).
