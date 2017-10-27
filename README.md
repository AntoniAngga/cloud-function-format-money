# cloud-function-format-money
cloud function untuk format money


The Endpoint nya ini https://us-central1-function-format-money.cloudfunctions.net/formatMoney?int={Nominal}
=======
| api                                                                                    | ket             |
|----------------------------------------------------------------------------------------|-----------------|
| https://us-central1-function-format-money.cloudfunctions.net/formatMoney?int={Nominal} | format currency |


change your {Nominal} into number that you want
example :

```javascript
{Nominal} -> 10000

output: 10.000
```
