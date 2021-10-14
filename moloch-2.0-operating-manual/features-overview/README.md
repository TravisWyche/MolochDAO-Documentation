# Features Overview

DAOhaus is currently available on Mainnet, xDAI, Polygon and Aribtrum. As a DAO summoner, here are the DAOhaus features that should matter to you.

> For more detailed explanations on various DAOhaus features, you can check out our Features explainers in our [user docs here](https://daohaus.club/docs/users/membership).

### Members, Shares and Loot[#](https://daohaus.club/docs/handbook/summoners/summoners-daohaus-features#members-shares-and-loot) <a href="members-shares-and-loot" id="members-shares-and-loot"></a>

DAOhaus helps you manage stakeholders within your DAOs (i.e. **Members**). **Members** are people or organisations that own **Shares** and **Loot** in your DAO. **Members** can own both **Shares** and/or **Loot**.

![](https://daohaus.club/assets/images/ua_memberview-6a1d062eac0e1cd8c997748e28ef4cbc.png)

> When a **Member** owns **Shares**, they have an economic share of the funds in the DAO's **Bank**, as well as voting rights in the DAO's **Proposals**.

> When a **Member** owns only **Loot**, they only have an economic share of the funds in the DAO's **Bank**, but not voting rights in the DAO's **Proposals**.

Non-members can join the DAO by requesting for Shares / Loot via a Membership **Proposal**. **Members** can leave the DAO through a **RageQuit** proposal, thereby withdrawing their pro-rated ownership of the **Bank**'s funds.

For more information on Membership, please refer to the [Members Explainer here](https://daohaus.club/docs/users/membership).

### Proposals & Voting[#](https://daohaus.club/docs/handbook/summoners/summoners-daohaus-features#proposals--voting) <a href="proposals--voting" id="proposals--voting"></a>

Decison making is done via **Proposals**, which will need to be voted on by **Members** (based on their respective Share counts)

![](https://daohaus.club/assets/images/how\_\_proposals-f29ed4c8c4644af334408bb7800c6a51.png)

Common types of **Proposals** are:

* Membership - Tributing capital and Requesting new shares to join the DAO
* Funding - Tributing or Requesting funds from the DAO to work on internal projects and improvements
* Whitelist - Request to add support for a new ERC20 token
* GuildKick - Request to forcibly remove a malicious member through a vote
* Minion - A contract that allows execution of arbitrary calls i.e swapping assets in the DAO bank

The stages for **Proposals** are:

* Submit Proposal
* Sponsor Proposal
* In Queue
* Voting Period
* Grace Period
* Ready for Processing
* Completed

For more information on Proposals, please refer to the [Proposals explainer here](https://daohaus.club/docs/proposals).

### Bank & Token[#](https://daohaus.club/docs/handbook/summoners/summoners-daohaus-features#bank--token) <a href="bank--token" id="bank--token"></a>

The **Bank** holds all the DAO funds, which include ERC-20 (excluding native tokens such as ETH, xDAI, MATIC on the respective chains) and ERC-721 NFTs.

![](https://daohaus.club/assets/images/bank_screenshot-e4b311ca97b1e385b05b9fd906169a6c.png)

> Native tokens must be wrapped first before being sent to the Bank. Alternatively, DAOs can set up a Minion that allows the holding of native tokens.

For an ERC-20 token to show up in the Bank's balance, the DAO must whitelist the token via a Whitelist Proposal (Tutorial here)

For more information on the Bank, please refer to the [Bank explainer here](https://daohaus.club/docs/users/bank).

### Minion & Boosts[#](https://daohaus.club/docs/handbook/summoners/summoners-daohaus-features#minion--boosts) <a href="minion--boosts" id="minion--boosts"></a>

Beyond the core functions of managing membership, proposals and funds, DAOhaus has **Minions** and **Boosts** that help to add extra functionality to your DAO (you can think of them like apps)

**Boosts**, in general, give you extra functionality to your DAO (e.g. adding a Discord bot to your DAO).

If you need to interact with smart contracts (e.g. swapping tokens, managing LP positions, etc.), **Minion** help you with making arbitrary calls to smart contracts.

For more information on Boosts, please refer to the [Boosts explainer here](https://daohaus.club/docs/boosts).
