# orderstatus

Order Status Helper
Summarize an order object for a support dashboard. The final summary should expose payment status, shipping status, item count, and whether the order needs attention.

Write these functions:

isPaid(order) should return true when payment.status is "paid".

hasShipped(order) should return true when shipping.status is "shipped".

getDeliveryMessage(order) should return a shipping message and include estimatedDelivery when the order has shipped.

needsAttention(order) should return true when the order is unpaid or has not shipped.

createOrderSummary(order) should return id, customerName, paid, shipped, itemCount, deliveryMessage, and needsAttention.

https://roadmap.sh/projects/js-order-status-helper
