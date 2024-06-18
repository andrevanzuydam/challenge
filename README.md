# challenge
Calculation challenge - Test Driven Development vs Standard Coding

Given the following number sequences which represent qty and tax inclusive amounts, calculate the percentage tax for each "line item" correct to two decimal places.
The total sum for all the line items should also be calculated as well as the total tax.  Assume the tax percentage is 15%.

Example Output

| Qty X Value    | Total  | Tax   |
|----------------|--------|-------|
| 1 X 115.00     | 100.00 | 15.00 |
| 2 X 115.00     | 200.00 | 30.00 |
| Totals: 345.00 | 300.00 | 45.00 |

Use the following `values` array in javascript to calculate the correct output.
```javascript
let values = [{qty: 2, value: 5.00}, {qty:6, value: 9.90}, {qty: 1, value: 100}, {qty: 5, value: 120.50}, {qty: 10, value: 115}, {qty: 8, value: 8.45}, {qty: 4, value: 65}];
```