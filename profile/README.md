# Tiny Traders

**Open-source trading infrastructure for Indian markets.**

One engine. Every strategy.

---

### What we build

| Package | What it does | Status |
|---|---|---|
| [**tt-connect**](https://github.com/Tiny-Trader/connect) | Unified Python broker API — auth, orders, portfolio, instruments, WebSocket streaming | [![PyPI](https://img.shields.io/pypi/v/tt-connect)](https://pypi.org/project/tt-connect/) |
| **tt-engine** | Trading engine — strategy execution, order lifecycle, backtesting, risk | Coming soon |

### Why

No end-to-end open-source solution exists for algorithmic trading in Indian markets. Existing tools solve one piece — condition builders for simple logic, fragile VPS setups for deployment, no structured backtesting for derivatives. We're building the reliable, programmable foundation that any strategy runs on.

### Get started

```bash
pip install tt-connect
```

```python
from tt_connect import TTConnect

with TTConnect("zerodha", {"api_key": "...", "access_token": "..."}) as broker:
    print(broker.get_profile().name)
    print("Funds:", broker.get_funds().available)
```

[Read the docs](https://tiny-trader.github.io/connect/) · [PyPI](https://pypi.org/project/tt-connect/) · [tinytrader.in](https://tinytrader.in)
