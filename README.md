# Coffee Shop Sales

An Excel-based sales analysis dashboard for a coffee shop chain operating across three New York City locations — **Astoria**, **Hell's Kitchen**, and **Lower Manhattan**.

![Coffee Shop Sales Dashboard](Screenshot%202026-07-02%20023050.png)

## Dataset

- **149,116** transactions
- Fields: `transaction_id`, `transaction_date`, `transaction_time`, `store_id`, `store_location`, `product_id`, `product_category`, `product_type`, `product_detail`, `unit_price`, `transaction_qty`
- Product categories include Coffee, Bakery, Tea, Coffee Beans, Drinking Chocolate, Flavours, Branded goods, and more

## Key Insights

| Metric | Value |
|---|---|
| Total Sales | $698,812.33 |
| Total Transactions | 149,116 |
| Avg. Bill / Person | $4.69 |
| Avg. Orders / Person | 1.44 |

- **Coffee** is the top-selling category (39% of sales), followed by an even split across Bakery, Tea, and Coffee Beans
- **Barista Espresso** is the best-selling product ($91,406), followed by Brewed Chai Tea, Hot Chocolate, and Gourmet Brewed Coffee
- Sales peak in the **morning rush between 8–10 AM** and taper off through the evening
- **Hell's Kitchen** and **Astoria** slightly outperform **Lower Manhattan** in footfall and revenue
- Daily order volume is fairly consistent Sunday–Friday, dipping slightly on Saturday
- Dashboard is filterable by **Month** and **Day of Week** using interactive slicers

## Files

| File | Description |
|---|---|
| `coffee shop sales..xlsx` | Raw transaction data + pivot tables/charts powering the dashboard |
| `Coffee Shop Sales Analysis.pdf` | Exported report of the full analysis |
| `Screenshot 2026-07-02 023050.png` | Preview of the interactive dashboard |

## Tools Used

- Microsoft Excel (PivotTables, PivotCharts, Slicers)

## How to Use

1. Download `coffee shop sales..xlsx`
2. Open in Excel and use the **Month Name** / **Day Name** slicers to filter the dashboard
3. Refer to `Coffee Shop Sales Analysis.pdf` for the static report version
