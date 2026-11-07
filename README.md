### Hi, I'm bobslayerX 👋

I build open-source tools for **crypto investigations** — following stolen funds
across blockchains and turning the trail into evidence people can act on.

🔍 **[crypttrace](https://github.com/bobslayerX/crypttrace)** — OSINT toolkit for tracing stolen crypto
on Ethereum and other EVM chains, Bitcoin, Litecoin, Dogecoin, Tron, Solana and TON

<a href="https://github.com/bobslayerX/crypttrace"><img src="https://raw.githubusercontent.com/bobslayerX/crypttrace/main/assets/web-ronin.png" alt="crypttrace investigating the Ronin bridge exploiter" width="760"></a>

- traces funds hop by hop to exchanges, mixers and bridges, and finds the exchange deposit — with the memo that names the account to freeze
- `check` — was this wallet drained? who took it, how many others were hit, what can still be saved
- `evidence` — a ready evidence pack for the exchange and the police, in English and Russian
- `funder` and `cluster` — who funded a wallet first, and which wallets one person set up
- exchange wallets labelled from the exchanges' own proof-of-reserves (Binance, Bybit, OKX, MEXC, HTX); phishing addresses from ScamSniffer; OFAC sanctions
- stablecoin freezes, address poisoning, investigations kept as case files, graph export to Gephi and Maltego

[![PyPI](https://img.shields.io/pypi/v/crypttrace)](https://pypi.org/project/crypttrace/)
[![selftest](https://github.com/bobslayerX/crypttrace/actions/workflows/selftest.yml/badge.svg)](https://github.com/bobslayerX/crypttrace/actions/workflows/selftest.yml)
[![Stars](https://img.shields.io/github/stars/bobslayerX/crypttrace?style=flat)](https://github.com/bobslayerX/crypttrace/stargazers)

```
pipx install "crypttrace[web]"
```

**Interests:** blockchain forensics · OSINT · Python

**Updates and case write-ups:** [Telegram — @method405](https://t.me/method405)
