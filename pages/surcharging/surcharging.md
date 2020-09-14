---
title: "Charging Card Fees to Clients"
keywords: surcharging
tags: [surcharging]
sidebar: gl_sidebar
permalink: surcharging.html
summary: This page outlines the surcharging feature in Gravity Legal, which allows firms to automatically bill clients for the cost of credit card processing at the point of payment. 
---

This feature is designed to comply with applicable rules and regulations. For a more detailed look at these rules, see our [surcharging guide by state](https://www.gravity-legal.com/financiallylegal/state-rules-on-charging-clients-a-fee-for-paying-with-credit-cards).

Setup
-----

1. Each firm needs to be approved for surcharging. To get approved, contact support. 
2. Once your firm is approved, you will see the following enabled, in **Settings - Firm Details - Surcharge Fees**.
![Surcharge Fee](images/surcharging/surcharge-fees.png)
3. The amount of the surcharge will display along with a toggle to turn this feature on and off at the firm level. To change the amount of the surcharge fee, contact support.

Payments
--------

1. Once enabled, this feature works without any intervention on the part of the firm. Any time a client pays, whether it be on a payment link, a standing link, a subscription or a stored payment method, these fees will be charged. 
2. When a client clicks on a payment link, they will see the following notice when credit/debit is selected.
![Payment Method](images/surcharging/payment-method.png)
3. If a client types in a credit card as opposed to a debit card, the surcharge will automatically be calculated and a new total displayed.
![Complete Payment](images/surcharging/complete-payment.png)
4. When the client clicks **Complete Payment**, the fee will be added to the transaction. 
5. When processing a credit card stored payment method, the surcharge will automatically be added to the transaction.
![Confirm Payment](images/surcharging/spm-confirm-payment.png)

Accounting For Fees
-------------------

1. If a transaction is to be deposited into your firm's operating account, the fee will be added to that transaction. For example, if the client owes $100 and pays by credit card, they will see a single charge for $103. This will display in **Reports** as follows:
![Operating Payment](images/surcharging/operating-payment.png)
2. If the transaction is to be deposited into the trust account, the amount of the fee will be deposited to the operating account, resulting in two transactions. For example, if the client owes $100 due to the trust account and pays by credit card, they will see one charge for $100 and one charge for $3. This will display in **Reports** as follows:
![Trust Payment](images/surcharging/trust-payment.png)
3. In the event of a split trust/operating payment made by credit card, all fees will be charged on the operating portion of the transaction. For example, if the client pays a $300 link ($100 of which is to be deposited into the operating accounts and $200 into the trust account), two transactions will be run. One $200 transaction is for the amount due to the trust account, and one $109 transaction is run on the operating account. The $109 transaction consists of the $100 amount due plus the $3 fee for that amount and the $6 fee for the trust amount. This will display in **Reports**  as follows:
![Split Payment](images/surcharging/split-payment.png)