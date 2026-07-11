# Vishnu Govind

Systems research at the intersection of market microstructure, tokenized settlement, and mechanism design. 15+ years across financial markets and distributed infrastructure; recent work focuses on quantifying the specific, nameable failure modes in DeFi and institutional-finance systems — peg stress, NAV divergence, settlement synchronization, parallel-execution contention — rather than building dashboards around them.

[LinkedIn](https://www.linkedin.com/in/vishnu-govind/) · [Writing on Medium](https://vishnugovind10.medium.com)

## Flagship Systems

Each of these follows the same discipline: a formally defined metric, a deterministic simulation or measurement surface, and an explicit scope section stating what the tool does not claim to do.

| Repo | Thesis |
|---|---|
| [`slotscope`](https://github.com/vishnugovind10/slotscope) | State-contention profiler for EVM contracts — quantifies the parallel-execution speedup ceiling a contract's storage layout actually permits, before deployment on a parallel EVM. |
| [`peglab`](https://github.com/vishnugovind10/peglab) | Stable-asset stress-testing lab — runs a stablecoin's collateral design against ten fixed adverse scenarios and returns the same deterministic risk metrics every time. |
| [`navbridge`](https://github.com/vishnugovind10/navbridge) | NAV integrity monitoring for tokenized funds — classifies why on-chain oracle NAV and off-chain administrator NAV diverge, and produces an audit-grade report. |
| [`institutional-crypto-funding-analyzer`](https://github.com/vishnugovind10/institutional-crypto-funding-analyzer) | Funding-rate research toolkit — runs competing carry strategies through one fee-and-slippage-aware backtest loop so results are actually comparable. |

## Market Infrastructure Research

Research prototypes exploring specific coordination and settlement failure modes in institutional and machine-economy infrastructure. These are modeling instruments and visual observatories, not production systems.

| Repo | Focus |
|---|---|
| [`Canton-Control-Plane`](https://github.com/vishnugovind10/Canton-Control-Plane) | Models "synchronization debt" — the internal operational cost a bank incurs when Canton Network's privacy partitioning splits one institution's own view of its balance sheet across isolated ledger streams. |
| [`temporal-liquidity-risk`](https://github.com/vishnugovind10/temporal-liquidity-risk) | Minimal model showing tokenized settlement can fail on timing alone — sufficient collateral, but liquidity demand arriving synchronously still hits a hard settlement constraint. |
| [`coordination-fabric`](https://github.com/vishnugovind10/coordination-fabric) | Deterministic observatory for how autonomous systems negotiate execution, routing, and congestion under infrastructure pressure. |
| [`inference-coordination-fabric`](https://github.com/vishnugovind10/inference-coordination-fabric) | The same coordination lens applied to scarce AI inference infrastructure under congestion and adversarial demand. |
| [`agentic-economy-observatory`](https://github.com/vishnugovind10/agentic-economy-observatory) | Interfaces for exploring the emerging machine economy as AI agents begin to behave as economic actors — requesting compute, settling obligations, building reputation. |

## Reference Implementations

Earlier, smaller tools — single-purpose trading and indicator scripts kept as reference implementations rather than production trading systems.

`TWAPexecution` · `MarketMaking` · `emacrossover` · `FXRisk` · `CorrelationIndicator` · `VolumeProfile` · `TradingviewSentimentIndicator` · `phantomwalletintegration` · `Decentralized-Exchanges`

## Writing

- [Designing the Next-Gen Crypto Exchange: Revolutionizing Market Dynamics for a Secure and Liquid Future](https://medium.com/@vishnugovind10/designing-the-next-gen-crypto-exchange)
- [Building the Next Generation of Crypto Market-Making Products: A Strategic Guide for CEOs and Product Managers](https://medium.com/@vishnugovind10/building-the-next-generation-of-crypto-market-making-products)
- [Revolutionizing DeFi: How BaseSwap is Redefining Decentralized Trading](https://medium.com/@vishnugovind10/revolutionizing-defi-how-baseswap-is-redefining-decentralized-trading)
