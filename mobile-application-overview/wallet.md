# Wallet

Every user will have a non-custodial multi-currency wallet within the application. All major fiat currencies will be supported for deposits and withdrawals via a third-party integration, and all balances within the app will be in TENKA, but will be shown with the proper conversion to the user in their local currency as well.

Users will be able to deposit funds and use their balance to participate in tournaments and send tokens to other users both internally and externally within the application. They will also be able to make withdrawals which can be paid out in fiat or crypto.

Deposits can be performed in either fiat or cryptocurrency. Fiat deposits will be processed via third-party integration, while crypto deposits will be directly to the Ignite Tournaments wallet.

Withdrawals will occur either as a crypto transaction via the wallet, or as through a third-party off-ramp provider.

Behind the scenes, when a user:

* deposits fiat to buy TENKA, their fiat will be stored in an escrow account, and they will be credited with a corresponding amount of TENKA tokens, which will be reflected in their balance.
* deposits crypto to buy TENKA, their crypto will be exchanged for fiat or stablecoins in order to remove exposure to volatility of the crypto markets, and a corresponding amount of TENKA will be credited to their account.
* makes a withdrawal request to fiat, their TENKA will either be bought back by the treasury, sold in one of our liquidity pools, or swapped via DEX connection. Users will be able to see the final amount they would receive before completing the withdrawal request, since this amount would be different than the total listed value of the tokens due to price impact during the exchange.
* makes a withdrawal request and keeps their TENKA, their TENKA will be sent to a wallet address they provide.

In the case where the price fluctuations in the token price (e.g. their TENKA balance becomes higher than what we hold from the deposit), this is when withdrawals will be balanced with a TENKA sale on an open exchange in order to prevent losses to the company, handled by liquidity pooling program, which we will offer and incentivize to the general public, or DEX.
