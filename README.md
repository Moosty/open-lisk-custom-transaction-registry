
```
Title:   Open Lisk Transaction Type Registration
Type:    Registration
Status:  Draft
```

## Abstract

This list contains all registered Lisk transaction types. Everyone can 
make a pull request to add new or update existing registrations.

## Motivation

Custom transactions for blockchain applications based on Lisk could be used in different blockchain applications
over and over again. To reduce type conflicts we would like to have a central point of registration of these transaction types.

## Registered transaction types

All these constants are used inside the transaction.

creator     | type        | status      | github
------------|-------------|-------------|-----------------------------------
HQ          | 0           | Deprecated  | [~~Transfer~~](https://github.com/LiskHQ/lisk-sdk/tree/v2.3.8/elements/lisk-transactions/src)
HQ          | 1           | Deprecated  | [~~Register second signature~~](https://github.com/LiskHQ/lisk-sdk/tree/v2.3.8/elements/lisk-transactions/src)
HQ          | 2           | Deprecated  | [~~Register delegate~~](https://github.com/LiskHQ/lisk-sdk/tree/v2.3.8/elements/lisk-transactions/src)
HQ          | 3           | Deprecated  | [~~Vote~~](https://github.com/LiskHQ/lisk-sdk/tree/v2.3.8/elements/lisk-transactions/src)
HQ          | 4           | Deprecated  | [~~Register multisignature account~~](https://github.com/LiskHQ/lisk-sdk/tree/v2.3.8/elements/lisk-transactions/src)
HQ          | 5           | Deprecated  | [~~Dapp~~](https://github.com/LiskHQ/lisk-sdk/tree/v2.3.8/elements/lisk-transactions/src)
HQ          | 6           | Deprecated  | [~~Transfer In~~](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 7           | Deprecated  | [~~Transfer Out~~](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 8           | V3          | [Transfer](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 9           | Deprecated  | [~~Second signature~~](https://github.com/LiskHQ/lisk-sdk/tree/v3.0.2/elements/lisk-transactions/src)
HQ          | 10          | V3          | [Register delegate](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 11          | Deprecated  | [~~Vote~~](https://github.com/LiskHQ/lisk-sdk/tree/v3.0.2/elements/lisk-transactions/src)
HQ          | 12          | V3          | [Multisignature](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 13          | V3          | [Vote](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 14          | V3         | [Unlock](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 15          | V3          | [Proof of misbehavior](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 100-199     | V4+         | [Transfer](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 200-299     | V4+         | [Delegate Registration](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 300-399     | V4+         | [Vote](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 400-499     | V4+         | [Multisignature Registration](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 500-599     | V4+         | [Unlock Vote](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 600-699     | V4+         | [PoM](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 700-799     | V4+         | [Reclaim](https://github.com/LiskHQ/lisk-sdk/tree/development/elements/lisk-transactions/src)
HQ          | 800-2500    |             | 
.           | 2501        |             |
JesusTheHun | ?           | V3          | [Lisk faucet transaction](https://github.com/JesusTheHun/lisk-transaction-faucet) 
.           |             |             |
Moosty      | 13000-13009 | V4          | [lisk-sprinkler (faucet)](https://github.com/Moosty/lisk-sprinkler)
Moosty      | 13010-13059 | V4          | [Recurring payment](https://github.com/Moosty/lisk-recurring-payment)                 
Moosty      | 13300-13399 | V3          | [Lisk-htlc](https://github.com/moosty/lisk-htlc#readme)
.           |             |             | 
.           |             |             | 
.           |             |             | 
