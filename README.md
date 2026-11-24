# SunSpa Financials

A source-controlled financial workflow and monthly reporting record for SunSpa South Africa.

## Purpose

Maintain a consistent monthly view of:
- Wix sales and order-level payments
- Sales excluding VAT and output VAT
- Product cost of sales (purchase prices excluding VAT)
- Operating expenses, including Yoco transaction fees
- Provisional operating profit
- The agreed 20% / 80% profit allocation

This repository currently contains the workflow, product catalogue, November 2026 source sales record and a provisional November report. It is a documentation/data foundation, not yet a live Wix integration or automated accounting application.

## Current November 2026 snapshot

Period: 1–24 November 2026.

- 4 paid orders
- Gross amount collected: R56,277.00
- Sales excluding VAT (Wix subtotal used): R48,936.52
- Cost of stock sold, excluding VAT: R37,976.15
- Recorded monthly expenses: R2,544.37
- Provisional operating profit: R8,416.00
- SunSpa retained allocation (20%): R1,683.20
- Nicom Consulting allocation (80%): R6,732.80

See [November report](reports/2026-11-report.md) and [workflow](docs/financial-workflow.md).

## Important accounting status

The November report is **provisional management reporting**, not a VAT return or signed-off set of accounts. It assumes the Wix subtotal of R48,936.52 is the correct revenue excluding VAT and that the supplied stock costs are VAT-exclusive. The Yoco fee estimate is 2.3% of gross collections. VAT treatment of Yoco, Google Ads and accounting invoices must be reconciled against supplier tax invoices. Confirm shipping treatment, refunds, discounts, delivery costs and any other expenses before finalising profit.

## Repository structure

- `docs/financial-workflow.md` — monthly close process and calculation rules
- `data/product-catalogue.csv` — product purchase costs excluding VAT and supplied retail prices
- `data/november-2026-sales.csv` — November order-level sales record
- `data/monthly-expenses.csv` — expense assumptions for November
- `reports/2026-11-report.md` — provisional November management report

Currency: South African rand (ZAR). VAT rate assumption used in this snapshot: 15%.
