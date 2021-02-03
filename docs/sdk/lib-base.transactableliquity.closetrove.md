<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [TransactableLiquity](./lib-base.transactableliquity.md) &gt; [closeTrove](./lib-base.transactableliquity.closetrove.md)

## TransactableLiquity.closeTrove() method

Close existing Trove by repaying all debt and withdrawing all collateral.

<b>Signature:</b>

```typescript
closeTrove(): Promise<TroveClosureDetails>;
```
<b>Returns:</b>

Promise&lt;[TroveClosureDetails](./lib-base.troveclosuredetails.md)<!-- -->&gt;

## Exceptions

Throws [TransactionFailedError](./lib-base.transactionfailederror.md) in case of transaction failure.
