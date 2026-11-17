<p align="center"><img src="mellora-logo.svg" width="72" alt="Mellora"></p>

<h1 align="center">Mellora</h1>
<p align="center"><b>Calm liquidity for Elysium and Robinhood Chain.</b><br>
<a href="https://mellora.org">mellora.org</a> · <a href="https://app.mellora.org">app.mellora.org</a> · <a href="https://x.com/MelloraLP">@MelloraLP</a></p>

Mellora is a non-custodial liquidity terminal for Uniswap. It reads the chain itself: live pools and trades,
liquidity depth on the chart, and position tools built around your own wallet.

This repository is Mellora's public home: what it does, where it runs, and what shipped when (see
[CHANGELOG.md](CHANGELOG.md) and the Releases). The application's source is not published here.

## Networks

| Network | Status | What works |
|---|---|---|
| Elysium (chain 99901) | Live | Pools, charts, trades and depth; create, collect, move and close Uniswap v4 positions; grids; swaps |
| Robinhood Chain (chain 4663) | Live · Beta | Pools, tokenized stocks, Uniswap v3 and v4 positions, swaps |

Switch networks in the app's header, or in your wallet.

## What you can do

- **Live market.** Every pool on the chain, ranked by what is actually trading: price, volume, buys and sells,
  straight from each swap.
- **Liquidity depth.** See where the liquidity sits around the price before you choose a range.
- **Charts and trades.** Candles built from every swap, and a live trade feed per pool and for the whole chain.
- **Positions and grids.** Create, collect, move and close Uniswap positions, or place a ladder of ranges in one
  transaction.
- **Swaps.** The better quote of Uniswap and KyberSwap.
- **Tokenized stocks** (Robinhood Chain). Stocks and ETFs in a view of their own, with tickers and company logos.
- **Range alerts.** A Telegram message when a position leaves its range or a ladder step fills:
  [@mellora_elysium_bot](https://t.me/mellora_elysium_bot) for Elysium,
  [@mellora_robinhood_bot](https://t.me/mellora_robinhood_bot) for Robinhood Chain.
- **Range Runner.** A two-minute game on real on-chain prices: keep the price inside your band.

## How it stays safe

- **Non-custodial.** No keys, no deposits, no accounts. Every transaction is built for your wallet and signed by you.
- **Exact approvals.** Approvals for the amount each action needs, never an unlimited allowance left behind.
- **Simulated first.** Each transaction is simulated against the chain before you sign it.
- **Known contracts only.** Positions go to Uniswap's own contracts. A KyberSwap route is checked against its known
  router before you sign.

## Official channels

Official news only at [mellora.org](https://mellora.org) and [@MelloraLP](https://x.com/MelloraLP).
Mellora has not launched a token. Anything else claiming to be Mellora is not us.

## Disclaimer

Mellora is an independent interface. It is not affiliated with, endorsed by or operated by Kinetiq, the Elysium
network, Robinhood Markets, Robinhood Chain, Offchain Labs, Paxos, KyberSwap, Uniswap Labs or the Uniswap
Foundation. Providing liquidity can lose money. Market data can be wrong or late.
