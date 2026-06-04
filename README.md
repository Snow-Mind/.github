# SnowMind ❄️

**Put your USDC to work. An AI agent finds the best safe yield for you — automatically.**

SnowMind is a non-custodial yield optimizer on the **Avalanche C-Chain**. You deposit USDC, and an on-chain AI agent moves it to whichever trusted lending protocol is paying the best risk-adjusted return at that moment. You stay in full control of your money the whole time.

---

## What it does, in plain words

- **You deposit USDC.** That's it — no complicated setup.
- **An AI optimizer watches the market** and parks your funds where the yield is best *and* safe.
- **It rebalances for you** as rates change across protocols, so you don't have to chase yield manually.
- **You can withdraw anytime.** Every withdrawal needs a fresh signature from *your* wallet — nobody else can move your money.

## Where your money goes

SnowMind only routes funds to well-known Avalanche lending protocols:

**Aave V3 · Spark · Euler V2 · Silo · Benqi**

Before sending funds anywhere, it health-checks each protocol (utilization, TVL, rate stability, de-peg detection) and weights the yield by risk. If a protocol looks unhealthy, it's skipped — and SnowMind can emergency-exit a protocol entirely if something goes wrong.

## Why it's safe

- **Non-custodial** — your wallet always owns the funds. SnowMind never holds your keys.
- **You own your smart account** — each user gets their own ZeroDev smart account.
- **Limited permissions** — the agent can *only* deposit, rebalance, or return funds to you. It can't send your money anywhere else.
- **All-or-nothing moves** — every rebalance happens in one atomic on-chain transaction. Funds never get stuck halfway.
- **Always watched** — daily balance reconciliation, operator kill switches, and real-time alerts on every important event.

> The only risk to your USDC is the normal risk of the underlying lending protocols — the same risk you'd take depositing into them yourself. SnowMind doesn't add new risk; it just finds you the best safe yield within strict rules.

## Fees

- **During beta: 0 fees.** You keep 100% of your yield.
- **Later: 10% of profit only** — never on your principal, and never on a loss.

## How it's built

| Part | Tech |
|---|---|
| Website & app | Next.js 15 (Vercel) |
| Backend / optimizer | FastAPI + Python (Railway) |
| Execution | Node.js + ERC-4337 account abstraction (ZeroDev + Pimlico) |
| Chain | Avalanche C-Chain (`43114`) |

---

## Links

| | |
|---|---|
| 🌐 Website | <https://snowmind.xyz> |
| 🚀 App | <https://app.snowmind.xyz> |
| 📚 Docs | <https://docs.snowmind.xyz> |
| 🐦 Twitter / X | <https://x.com/snowmind_xyz> |

---

<sub>SnowMind is a non-custodial DeFi application. Using DeFi protocols carries risk; please do your own research. Nothing here is financial advice.</sub>
