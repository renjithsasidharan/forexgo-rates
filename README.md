# forexgo-rates

Daily exchange rates for the ForexGo app (base USD), fetched from [Frankfurter](https://frankfurter.dev/) by a GitHub Action.

CDN: https://cdn.jsdelivr.net/gh/renjithsasidharan/forexgo-rates@main/rates.json

```json
{ "base": "USD", "updated": "2026-10-31T16:30:00Z",
  "rates": { "INR": { "rate": 95.12, "date": "2026-10-31" }, ... } }
```

Convert: `amount × rates[to].rate ÷ rates[from].rate`
