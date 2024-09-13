A payments orchestrator is facing a spike in payment failures. Goal is to identify what is causing the spike in payment failures.

#### Problem Statement:
##### You work for a payments orchestrator company, that enables seamless integration and management of multiple payment methods and gateways for businesses to optimize their payment processing.
##### On Feb 14, 2020, you get calls from many merchants. Merchants tell you that they are seeing a spike in customer complaints and want you to check if there are any issues. You tell them that you are going to revert to them in a few hours.

#### Data:
##### You have the payment transactions data for Feb 12, 13 and 14.
##### Below is a description of different columns in the data set
##### hr : Start hour of the transaction
##### mid : Merchant Identifier
##### t : Total number of transactions
##### success : Total number of `successful` transactions
##### pg : Payment Gateway, who collects money on behalf of the merchant
##### pmt : Payment Method Type such as cards, UPI etc.,
##### sub_type : The subtype of payment option chosen by the customer
##### bank : The customer bank account from which the money is sent
