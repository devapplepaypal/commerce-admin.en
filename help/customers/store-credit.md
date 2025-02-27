---
title: Store Credit
description: Store credit is an amount that is restored to a customer account. Customers can use their store credit to pay for purchases, and administrators can use store credit for cash refunds.
exl-id: 1fe627dd-5c49-4ff8-85e0-3c987285726d
---
# Store Credit

{{ee-feature}}

Store credit is an amount that is restored to a customer account. Customers can use their store credit to pay for purchases, and administrators can use store credit for cash refunds. Gift card balances can be credited to the customer's account, instead of using the gift card code for future purchases.

After an order is paid and invoiced, all of the order, or a portion of it, can be refunded by [issuing a credit memo](../stores-purchase/credit-memo-create.md). A credit memo differs from a refund because the amount of the credit is restored to the customer's account where it can be used for future purchases. In some cases, a refund can be given at the same time that a credit memo is issued, and applied to the customer's balance of store credit. The amount of store credit that is available in the customer's account is specified in the configuration.

>[!NOTE]
>
> [Zero Subtotal Checkout](../stores-purchase/zero-subtotal-checkout.md) payment method needs to be enabled in the case that store credit covers the order total.

## Store credit workflow

1. **Customer login** - Customer logs into account before beginning the checkout process.

1. **Use Store** - Credit During the [!UICONTROL _Review & Payments_] step of the checkout process, the customer selects [!UICONTROL _Use Store Credit_] as a payment option. The available balance is displayed in parentheses. If the available balance is greater than the order grand total, the other payment methods are no longer displayed.

1. **Credit applied to order** - The amount of store credit that is applied to the order appears with the order totals, and is subtracted from the grand total.

1. **Customer balance adjusted** - The customer's available balance is adjusted when the order is placed.
