# house-cost

Pure frontend house cost calculator for Sweden.

## Run with Docker Compose

```bash
docker compose up --build
```

Open: http://localhost:8081

## Inputs

- House price
- Expected down payment
- Loan interest rate (slider)
- Yearly property tax/fee (optional)
- Utilities (monthly, optional)
- Home insurance (monthly, optional)
- Existing pantbrev available (optional)
- Existing lagfart amount to include (optional)
- One-time cost spread years (optional)

The app also supports home insurance input and shows an expandable detailed breakdown,
including Swedish one-time costs such as lagfart and pantbrev.
