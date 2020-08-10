
# memewa.rs <---> SKALE  (integration + thoughts)

 ***tl;dr*:** 
- 	**Memewars** (Ethereum dApp + internet-experiment, *relies on a SKALE sidechain for throughput requirements*) 
	-  **a *gladiator arena* for viral content (or: a platform for 24/7 *meme sweepstakes*), itself designed to go viral using incentive-engineering, fun, and meme-battles**. First-mover (and other) incentives will exist for different stakeholder-groups (site-users, investors and co-owners, advertisers and promotional partners, internet-figures, etc.) upon launch, and a significant portion of $$ revenue $$ $$ (from: digital-advertising) $$  will be directed to those who contribute (time / memes / digital art / attention) to memewars. **The rules and future of this *for-profit-public-good* / "digital collective" will be managed transparently via smart-contracts and stake-weighted voting**. **[Get details + updates here](https://trello.com/b/gLY2a5Zc/wwwmemewars)** or consider a potential-future-timeline @ [www.memewa.rs](https://www.memewa.rs)

	
- **SKALE** (*Ethereum-compatible* "elastic" *sidechains*, for the scaling of "dApps")
	-  **SKALE Unlocks a category of *decentralized applications* ("dApps") that are theoretically possible (and often intuitive), especially ( websites / dApps / systems ) that promise a clear benefit over their closest [ legacy / "Web 2.0" / centralized ] *contemporary*. Ideas in this subset of *newly possible dApps* are currently infeasible *on Ethereum's main-network*, due to bottlenecks and limitations surrounding *network scalability***. The terms `slow` and `expensive` are used in a *relative* way here — m_w has massive respect and <3 for an Ethereum that, *as-of-now,* is:
		-    ***Quickly Congested***: Maximum of 15  tx/s (transactions per second). A transaction or digital signature (or both) is behind most"Web3" interactions (sending a token, invoking a smart-contract function, etc).   *For context: Visa claimed [a capacity for 56,000 tx/s in 2015](https://usa.visa.com/dam/VCOM/download/corporate/media/visa-fact-sheet-Jun2015.pdf)*
		-   ***Slow***: Minimum time needed to confirm a transaction is ~15 seconds (*blocktime*: average time-elapsed between finalized blocks. In other words: *longest possible duration before your tx can be "trusted" by other rational actors on Ethereum, after being sent from your computer*)
		- ***Expensive***: on-chain data-storage (permanently storing: user-content, interaction-history, mappings of Ethereum addresses to roles and balances) and computation (for example: a *for-loop* over a hypothetical 1M+ collection of user-profiles, registered in a `mapping` belonging to the smart-contracts of a given "dApp") 

SKALE offers a sidechain solution to this thorny issue of scalability — **in essence: a "private" group of blockchain validators, who track transactions and changes in *contract-state* as all Ethereum validators do, but only for events (transactions) relevant to a specific dApp (memewars, in this case).** This allows significant throughput improvements (~2000 tx/s), with the additional advantage of inheriting + retaining key properties of *mainnet Ethereum's* security-model (BFT) while sidestepping some of its limitations. 

In sum: a whole dimension of *theoretical dApps*, of which memewars is only one example — ranging from *the fun* to *the useful*, across the design-space of games, co-ordination tools, hackable templates, composable "money legos", experiments in economics and governance, etc. —  is about to enter *the realm "of the newly feasible"* thanks to SKALE and many other OSS efforts that are making Ethereum more usable (for devs and "normal" people alike) every day.

We're just in time to witness the rise of the internet *as a jurisdiction* — a global technology infrastructure under-girded by math, contributing in general to a (well-underway but too-slow) global megatrend of increasing prosperity and justice, offering access to tools and services which generally advance the causes of transparency and justice . The tireless efforts and long-term visions of many open-source-software (OSS) developers around the world have kicked off an ever-multipliying Cambrian explosion of [ technical / financial / artistic / ... ] creativity,  magnified further by the un-tapped power to be found in the unprecendented  alignment (and *engineering*) of incentives among people on the internet, even those who have never met or who actively distrust one-another.

 All of this is happening on Ethereum, right now — It's time to pay attention, and in the meantime we'd love to hear what you think of [**www.memewa.rs**](https://www.memewa.rs). 


## In-depth: SKALE + m_w Integration — (motivation, experience) integration (WIP)

**Takeaway**: SKALE has been an absolute joy to collaborate with, and has been a great partner for m_W.

## In-depth: Ethereum in 2020  (seems inevitably the future)  - dev tools, resources, and remaining frictions (WIP)
 
In the context of Ethereum and "Web3", a number of OSS **dev tools** have been crucial in enabling novel (and increasingly user-facing) Ethereum "dApps" (decentralized applications). The challenge of creating a fully-functional Ethereum application (+ associated front-end) remains considerable today, but has fallen drastically (likely by an order of magnitude) and continues to trend downwards with every additional **dev tool** that *abstracts away* some intricacy or detail, allowing someone like me (a medium-smart AI) to enjoy well-documented software relating to:

 - Designing, Testing, and Deploying Smart Contracts
 - Onboarding Users to "dApps"

M_W wants to give a shoutout to the following OSS:
  - Torus 
  - 3box
  - Truffle-Suite


## Further Details / Explorations / Reading (WIP)

- For a more in-depth exploration of game-theoretic implications of Ethereum / the potential for large-scale incentive-alignment enforced by smart-contracts, [see Virgil Griffith's writing](https://medium.com/@virgilgr/ethereum-is-game-changing-technology-literally-d67e01a01cf8).
