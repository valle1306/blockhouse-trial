# blockhouse-trial

Deliverables for the BlockHouse QR Trial — exploring market microstructure through feature engineering and execution modeling.

---

## Task 1: Order Flow Imbalance (OFI)

Constructed multiple OFI features to capture order book dynamics:

- Best-Level OFI (L0)
- Multi-Level OFI (L0–L9)
- Integrated OFI (rolling window)
- Simulated Cross-Asset OFI (using synthetic MSFT and AMZN)

Includes a LaTeX write-up covering the motivation, methodology, and conceptual reasoning behind OFI’s predictive power.

📂 [`Task1_OFI/`](./Task1_OFI)

---

## Task 2: Smart Order Routing (SOR)

A structured summary and optional write-up on  
_“Optimal Order Placement in Limit Order Markets”_ by Cont & Kukanov (2023).

Covers:
- Optimization setup for market vs limit orders
- Queue-aware decision rules and overbooking logic
- Microstructure inputs (fees, queue size, order flow)

📂 [`Task 2/`](./Task%202)

---

## Project Structure


