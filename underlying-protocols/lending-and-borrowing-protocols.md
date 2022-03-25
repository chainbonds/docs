# 🔙 Lending & Borrowing Protocols

Lending & Borrowing Protocols include different mechanisms to generate yields for liquidity providers. &#x20;

Let's say Alice wants to borrow 100 USDC of asset from a lending & borrowing protocol. To borrow assets, she must lock up a certain amount of collateral to give security to the protocol, that she can pay back part of what she has lent. This value is usually between 0% and 100% of the total assets borrowed, but can also go above that. On top of the collateral, when Alice pays back the borrowed USDC, she must pay back the 100 USDC plus interest. Depending on the demand and supply of the assets, this interest can commonly range to somewhere between 1% and 20%. Let's assume that in this case, Alice has to pay a 12% interest.

But where do the borrowed assets come from? These come from Bob, who holds USDC, and who doesn't want his USDC to stay idle in his Phantom wallet. The protocol provides security to Bob, as the borrower (in this case Alice), has to lock up collateral. Furthermore, the protocol incentivizes Bob by providing him with a large part of the interest that Alice has to pay. Bob is offered around 10% of interest to the USDC he has provided. The rest of the 2% (12% - 10%), goes to the protocol as profit.

In reality, the interest rates change on a daily or hourly basis, especially in pools with less liquidity, as the ratio between supply and demand changes quickly.&#x20;

There are a vast number of borrow & lending protocols on Solana. Some includes:

* [Solend](https://solend.fi) which includes autonomous interest rate calculation across 25 assets and 6 pools.
* [Invariant](https://projectlarix.com) which also includes a dynamic interest rate model, including more collateral types such as stablecoins, synthetic assets and NFTs.
* [Jet Protocol](https://www.jetprotocol.io) which also includes a dynamic interest rate model
* &#x20;[Anchor protocol](https://www.anchorprotocol.com) which provides a low volatility interest rate to the depositors

In our currently Iteration, we do not support and borrow & lending protocols. We are working on integrating with Larix and Solend, whichever proves to be faster and have better APIs.

{% hint style="info" %}
**Don't see your favorite protocol or have questions?** DM us on Twitter or shoot us an e-mail at contact@qpools.finance and we will get back to you asap!
{% endhint %}
