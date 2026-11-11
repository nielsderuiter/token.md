# token.md

company.md, for tokens. One markdown file an AI agent can read to learn what is known about a token, with its sources listed at the end.

- `index.html` is the generator. Paste a token address and it builds a token.md from live data in your browser. It is a single static page with no server and no API keys.
- `token-md-spec-v0.1.md` is the spec: which sections and fields a token.md has, and where each one comes from.
- `llms.txt` points agents to the spec.

## What a file contains

- Read from the chain and data providers: deploy contract and launch transaction, launchpad, contract powers, pools and liquidity, holders, price.
- Written by the issuer: headline, description, links, tags, token utility and team members, in one fenced block marked as unverified.
- Stated as missing: a field with no value says `none`, `unknown` or `not fetched`.
- The same facts once more as a JSON block with fixed keys and raw numbers.

The file gives no score and no recommendation.

## Launchpads

A token is tied to a launchpad only when that launchpad's own deploy contract created it or holds a record for it. Recognized today: Ascend, Backable, Bonk.fun, Clanker, Flap, Float, Four.meme, Frontier, Genius.fun, Long.xyz, Meteora Dynamic Bonding Curve, Montra, Pons, Pump.fun, Rise.rich, StonkBrokers, StonkFun, Torchpad.fun, Umia, Virtuals Protocol.

## Data sources

Blockscout, public Solana, BNB Chain, Base and Elysium nodes, DexScreener, GoPlus, GeckoTerminal, RugCheck, GitHub, RDAP.

## Status

Spec 0.1, a draft. Corrections and additions are welcome as issues or pull requests.

Draft by [@notneils](https://x.com/notneils). Not investment advice.
