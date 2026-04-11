# Business Questions — Olist E-Commerce Analysis

## Order Status & Delivery

1. **Delivery rate** — what % of orders were successfully delivered, on a monthly basis
2. **Delivery time** — time elapsed from `order_purchase_timestamp` to `order_delivered_customer_date`
3. **On-time performance** — how many orders were delivered on time, early, or late (compare `order_delivered_customer_date` vs `order_estimated_delivery_date`)

## Sales & Revenue

4. **Sales by geography** — number of orders and total revenue by `customer_city` and `customer_state`
5. **Order value & size** — average order value (AOV) and average number of items per order
6. **Freight vs price** — freight contribution vs product price in total revenue, broken down by customer city

## Customers

7. **Orders per customer** — distribution of order frequency; top 10 customers by number of orders and by total revenue

## Payments

8. **BNPL vs straight purchases** — split of BNPL vs non-BNPL orders; correlation between BNPL usage and order price
9. **Payment type distribution** — most prominent payment types by order count and volume
10. **Payment methods per order** — average number of unique payment methods used per order
11. **Installment depth** — average number of installment months for BNPL orders

## Products

12. **Product variety per order** — average number of unique products per order

---

*Next step: for each question, identify the columns needed, the aggregation logic, and the appropriate chart type.*
