# Sample Data

`sample_transactions.csv` is a synthetic dataset created for this repository. It is not a real bank statement and does not contain actual names, account identifiers, transaction identifiers, or balances.

The file uses four columns:

| Column | Description |
| --- | --- |
| `Date` | Date of the sample transaction |
| `Description` | Bank-style transaction description used by the cleaning rules |
| `Amount` | Positive values represent money in; negative values represent money out |
| `Balance` | Synthetic running balance after each transaction |

The descriptions intentionally include variations such as card purchases, transfers, subscriptions, and payments so the notebook can demonstrate classification and merchant cleaning.
