# Spencer Heflin

Treasury and balance sheet risk specialist based in London. I have spent 12 years in asset-liability management (ALM) across US and UK banks, covering interest rate risk in the banking book (IRRBB), liquidity, hedging and behavioural modelling of deposits and mortgage prepayments.

I now apply the same discipline to on-chain lending: collateral, liquidation and liquidity risk in DeFi protocols.

## Projects

### [aave-wsteth-stress](https://github.com/heflinspencer/aave-wsteth-stress)

Liquidation and bad-debt stress model for wstETH collateral on Aave v3 Ethereum. *In progress.*

- Stresses one-hour ETH shocks of 20%, 30% and 40%, plus a wstETH/ETH depeg, against on-chain DEX depth, oracle latency and liquidator capacity.
- Pulls every position from the chain at a pinned block and reconciles the model's health factors to Aave's own.
- Fully reproducible: data manifests, a running assumptions log and offline tests.

`Python` `web3` `pandas` `pytest`

### [alm_models](https://github.com/heflinspencer/alm_models)

Economic value of equity (EVE) engine with behavioural models for both sides of a bank balance sheet. Synthetic data only.

- Mortgage prepayment: a fitted S-curve on rate incentive, with a random forest trained on the residuals for loan-level effects.
- Non-maturity deposits: asymmetric rate pass-through (betas) with a zero floor.
- Revalues the portfolio under parallel and regulatory rate shocks.

`Python` `SciPy` `scikit-learn` `pytest`

## Background

- **Experience:** Vida Bank (balance sheet management), Yorkshire Building Society (treasury financial modelling), Raymond James (ALM advisory for client banks)
- **Education:** MSc Computing, Queen Mary University of London; MS Accountancy; BBA International Business
- **Tools:** Python, SQL, pandas, scikit-learn, web3

## Contact

[LinkedIn](https://www.linkedin.com/in/spencer-heflin-758795278/)
