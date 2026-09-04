# Product Requirements Document (PRD)
## Car Refinishing Inventory & Sales Tracker (V1)

## Target User
Independent retail owners supplying car refinishing products (paints, abrasives, clear coats) to body shops and DIYers.

## Problem
Managing a large, highly specific stock list manually causes discrepancies, stockouts of popular items, and inefficient daily sales tracking.

## Main Journey
1. **Setup:** The owner adds a new product (e.g., "Gloss Clear Coat 1L") with its price and starting quantity.
2. **Transaction:** A customer buys the product. The owner quickly logs the sale in the app.
3. **Automation:** The system automatically deducts the sold quantity from the inventory database.
4. **Review:** The owner views a simple dashboard showing today's total revenue and a list of low-stock items.

## V1 Features (Core Value Only)
- **Inventory Management:** Add, edit, and delete products (Name, Category/SKU, Price, Current Stock).
- **Sales Entry System:** A simple interface to record a transaction by selecting a product and entering the quantity sold.
- **Auto-Reconciliation:** Automatic deduction of sold items from the master inventory.
- **Basic Dashboard:** View current stock levels, low-stock alerts, and total sales (daily/weekly).

## NOT NOW Features (Saved for V2+)
- Barcode or QR code scanning.
- Supplier integrations or automated purchase orders.
- Customer accounts or loyalty tracking.
- Multi-store or multi-employee role management.
- Complex tax/discount calculations.

## Constraints
- **Speed:** Logging a sale must take under 15 seconds to avoid slowing down the checkout counter.
- **Simplicity:** The UI must be straightforward enough for an owner who is used to pen-and-paper to learn in 5 minutes.
- **Tech Stack:** Must be web-based or easily accessible on a desktop/tablet at the shop counter.

## Success Condition
The owner completely replaces their paper ledger/spreadsheet with this tool, can log a transaction in under 15 seconds, and trusts the system's low-stock alerts without doing a manual physical count.
