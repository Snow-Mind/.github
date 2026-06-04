<div align="center">

<img src="snowmind-logo.png" alt="SnowMind" width="140" />

# SnowMind ❄️

**Autonomous, non-custodial USDC yield on Avalanche.**

Deposit USDC and an on-chain AI agent continuously rebalances it into the best risk-adjusted yield across Avalanche's leading lending protocols — within strict on-chain safety rules. You stay in full control of your funds at all times.

[🌐 Website](https://snowmind.xyz) · [🚀 App](https://app.snowmind.xyz) · [📚 Docs](https://docs.snowmind.xyz) · [🚀 Launch post](https://x.com/snowmind_xyz/status/2060465962818887994) · [🐦 X](https://x.com/snowmind_xyz) · [💼 LinkedIn](https://www.linkedin.com/company/snowmindxyz/)

</div>

---

## What SnowMind does

- **You deposit USDC.** No complex setup, no manual yield-chasing.
- **An AI optimizer continuously routes your funds** to whichever trusted protocol offers the best risk-adjusted return at that moment.
- **It rebalances automatically** as rates shift across protocols.
- **You can withdraw anytime.** Every withdrawal requires a fresh signature from *your* wallet — no other party can ever move your money.

## Where funds go

SnowMind only routes capital to established Avalanche lending protocols:

**Aave V3 · Spark · Euler V2 · Silo · Benqi**

Before any allocation, each protocol is health-checked (utilization, TVL, rate stability, de-peg detection) and its yield is weighted by risk. Unhealthy protocols are skipped, and SnowMind can emergency-exit a protocol entirely the moment something looks wrong.

## Security

- **Non-custodial** — your wallet always owns the funds. SnowMind never holds your keys.
- **Your own smart account** — each user gets a dedicated ZeroDev smart account.
- **Scoped permissions** — the agent can *only* deposit, rebalance, or return funds to you. It cannot send your money anywhere else.
- **Atomic moves** — every rebalance executes in a single all-or-nothing on-chain transaction. Funds never get stuck mid-move.
- **Always monitored** — daily on-chain reconciliation, operator kill switches, and real-time alerts on every critical event.

> The only risk to your USDC is the inherent risk of the underlying lending protocols — the same exposure you'd take depositing into them directly. SnowMind adds no new risk; it routes you to the best risk-adjusted yield within strict guardrails.

## 🛡️ Audited

SnowMind's smart account architecture and backend have been security-audited by **[Firepan](https://firepan.com/)**.

## Fees

- **During beta: 0 fees.** You keep 100% of your yield.
- **Later: 10% of profit only** — never on principal, and never on a loss.

## Built with

| Part | Tech |
|---|---|
| Website & app | Next.js 15 (Vercel) |
| Backend / optimizer | FastAPI + Python (Railway) |
| Execution | Node.js + ERC-4337 account abstraction (ZeroDev + Pimlico) |
| Chain | Avalanche C-Chain (`43114`) |

## Backed & supported by

- **[Avalanche](https://www.avax.network/)** ([@avax](https://x.com/avax)) — built on the Avalanche C-Chain
- **Team1 USA**

---

<div align="center">
<sub>SnowMind is a non-custodial DeFi application. Using DeFi protocols carries risk; please do your own research. Nothing here is financial advice.</sub>
</div>
