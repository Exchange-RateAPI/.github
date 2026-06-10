## Free Exchange Rate API for 160+ Currencies

[![Powered by Exchange-RateAPI](https://img.shields.io/badge/Powered%20by-Exchange--RateAPI-blueviolet.svg)](https://exchange-rateapi.com)

[![API Status](https://img.shields.io/badge/API-Online-brightgreen)](https://exchange-rateapi.com) [![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/Exchange-RateAPI)

**Exchange Rate API** provides accurate, real-time and historical currency exchange rate data through a simple REST API. Mid-market rates from Reuters/Refinitiv updated every 60 seconds, no markup, no spread.

### Quick Start

```bash
curl -H "Authorization: Bearer YOUR_API_KEY" \
  "https://exchange-rateapi.com/api/v1/rates?source=USD&target=EUR,GBP,JPY"
```

```json
[
  { "source": "USD", "target": "EUR", "rate": 0.9234, "time": "2026-05-25T12:00:00Z" },
  { "source": "USD", "target": "GBP", "rate": 0.7891, "time": "2026-05-25T12:00:00Z" },
  { "source": "USD", "target": "JPY", "rate": 149.52, "time": "2026-05-25T12:00:00Z" }
]
```

### Official SDKs

| Language | Package | Install |
|----------|---------|---------|
| **JavaScript/TypeScript** | [@exchangerateapi/sdk](https://www.npmjs.com/package/@exchangerateapi/sdk) | `npm i @exchangerateapi/sdk` |
| **Python** | [exchange-rateapi](https://pypi.org/project/exchange-rateapi/) | `pip install exchange-rateapi` |
| **PHP** | [exchangerateapi/sdk](https://packagist.org/packages/exchangerateapi/sdk) | `composer require exchangerateapi/sdk` |

### Links

[Website](https://exchange-rateapi.com) | [API Docs](https://exchange-rateapi.com/docs/) | [Get Free API Key](https://exchange-rateapi.com/register/) | [Pricing](https://exchange-rateapi.com/pricing/)
