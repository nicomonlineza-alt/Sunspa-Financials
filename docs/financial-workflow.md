# SunSpa Financials — Monthly Workflow

## 1. Reporting period and source records

At month-end, export or retrieve all Wix orders for the reporting month. Keep the order ID, order date, product description, quantity, gross amount collected, discounts/refunds, shipping and tax amounts, and payment status.

Only include orders that are successfully paid when reporting cash collected. Separately track unpaid, cancelled, refunded and partially refunded orders. Reconcile Wix totals to Yoco settlements and the bank statement.

## 2. VAT treatment

Use VAT-exclusive values for the profit-and-loss calculation.

- Standard VAT rate used in this workbook: 15%, subject to confirmation of the applicable rate and transaction treatment.
- For a VAT-inclusive amount at 15%, VAT component = inclusive amount × 15 / 115.
- VAT-exclusive amount = inclusive amount / 1.15.
- For supplier costs explicitly supplied as VAT-exclusive, record the net cost and track input VAT separately only where a valid tax invoice exists and the expense qualifies.
- Keep output VAT and input VAT separate from revenue and operating expenses. Do not treat VAT collected as income.
- Use the actual tax invoice and settlement statement for Yoco fees, Google Ads and accounting fees. Do not assume all fees have the same VAT treatment.

For each month, verify whether the Wix subtotal represents product revenue excluding VAT and whether shipping, discounts and refunds are represented correctly. Reconcile this before closing the month.

## 3. Cost of goods sold (COGS)

For each item sold:
1. Match the Wix product to the product catalogue.
2. Multiply the VAT-exclusive unit purchase cost by quantity sold.
3. Sum all items to calculate COGS.
4. Investigate products without a matching cost, bundles, accessories, replacements or stock adjustments rather than guessing.

Use the purchase cost applicable to the actual stock batch where costs have changed. The catalogue is a reference list and should be updated with effective dates when supplier prices change.

## 4. Operating expenses

Record actual monthly expenses and supporting invoices:
- Google Ads: budget/actual expense (current planning figure R1,000 per month)
- Accounting: current planning figure R250 per month
- Yoco: current estimate 2.3% of each transaction; replace estimate with actual Yoco fee statement when available

The November estimate applies 2.3% to gross paid collections of R56,277.00, giving R1,294.37. Confirm whether the 2.3% rate is VAT-inclusive or exclusive and whether additional fees apply.

Include other legitimate business costs when applicable, such as delivery, packaging, bank charges, refunds, chargebacks and platform fees.

## 5. Provisional operating profit

Management calculation:

**Operating profit before tax = sales excluding VAT − COGS excluding VAT − operating expenses excluding recoverable VAT.**

This is a management estimate, not necessarily taxable profit or distributable profit. Adjust for accruals, inventory movements, depreciation, income tax and other accounting items with the accountant as appropriate.

## 6. Profit allocation

After the month's profit has been reviewed and approved:
- 20% of positive net profit is retained/invested in SunSpa.
- 80% is allocated to Nicom Consulting.

Do not allocate a loss. If profit is zero or negative, both allocations are zero. The 20/80 split is a management allocation rule and does not by itself establish a legal dividend, loan, service fee or tax treatment. Have the accountant confirm the correct legal and tax mechanism before transferring funds between entities.

## 7. Monthly close checklist

- [ ] Confirm reporting dates and retrieve all Wix orders.
- [ ] Reconcile paid orders to Yoco settlements and bank deposits.
- [ ] Check refunds, cancellations, discounts and shipping.
- [ ] Confirm sales excluding VAT and output VAT.
- [ ] Match every sold product to its correct SKU and cost.
- [ ] Reconcile COGS and stock movements.
- [ ] Enter actual operating expenses and attach invoices.
- [ ] Replace estimated Yoco fees with actual charges.
- [ ] Reconcile input VAT and output VAT with tax invoices.
- [ ] Calculate provisional operating profit.
- [ ] Review results with the accountant.
- [ ] Apply the 20% / 80% allocation only after approval.
- [ ] Save the monthly report and source exports in this repository.

## 8. Data quality rules

Never silently infer a missing product cost, VAT amount, payment status or fee. Mark it as pending and exclude it from a finalised result until verified. Preserve original source exports and record corrections in a dated note.
