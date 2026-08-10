CardaPay: A Cardano Payments Proposal Still at the Conceptual Stage

CardaPay wants to simplify payments within the Cardano ecosystem. For now, we know quite a lot about what it proposes to build, and much less about who is building it or how far development has actually progressed.

Paying online looks simple: you choose a product, enter a few details, and press a button. Behind that apparently innocent gesture are banks, payment processors, card networks, currency conversions, fraud controls, identity checks, and a respectable number of intermediaries getting paid for joining the party.

CardaPay proposes building an alternative on Cardano: infrastructure for sending and receiving payments with ADA, stablecoins, and other digital assets, along with tools that would allow merchants and developers to integrate those transactions into their own services.

The important word here is “proposes.”

The publicly available information describes CardaPay’s vision in considerable detail, but it does not yet allow us to confirm the existence of an operational platform, a test version, an active repository, or a publicly identified team.

For now, we have the blueprints. The building itself remains considerably harder to find.

What is CardaPay?

CardaPay was presented in Project Catalyst Fund 14 as a decentralized payment platform built on Cardano. The proposal requested 75,000 ADA for a six-month development period, but its status is listed as “Not approved,” meaning it did not receive the requested funding in that round.

The project describes itself as a possible alternative to traditional services such as PayPal and Stripe. Its goal would be to allow individuals and merchants to receive payments using Cardano assets, with lower costs, faster settlement, and less reliance on financial intermediaries.

It would not simply be an application for transferring ADA between two wallets. The proposal describes a much broader infrastructure:

A non-custodial mobile wallet.
Payments between individuals and merchants.
Support for ADA, stablecoins, and other native assets.
Smart contracts for payments, escrow transactions, and subscriptions.
An API and developer tools.
Plugins for Shopify, WooCommerce, and Magento.
Optional identity systems, KYC, and anti-money laundering monitoring.
Integration with Hydra to process transactions more quickly.

A non-custodial wallet means that users would retain control of their private keys and therefore their funds. CardaPay would not hold the money in the same way a bank account or centralized platform does.

In other words, the project is not merely proposing to add a payment button to a website. It aims to build much of the machinery that would need to exist behind that button: wallet, contracts, merchant tools, compliance, and scalability included.

A modest little list, as you can see.

What problem is it trying to solve?

The proposal starts from a real problem: international payments can be expensive, take several days, or simply not be equally accessible in every country. It also questions the power centralized providers have to restrict accounts, reject transactions, or decide who can use their services.

In response, CardaPay proposes a system in which people would retain control of their funds and send payments directly from their wallets.

For merchants, the idea would be to provide integrations similar to those already offered by traditional payment gateways. An online store could install a plugin, accept Cardano assets during checkout, and later review its transaction history.

For developers, CardaPay proposes an API and other tools that would allow payments to be integrated into applications, digital marketplaces, or subscription services without having to build all the blockchain infrastructure from scratch.

The proposal also includes escrow contracts. Put simply, the money would remain temporarily locked until an agreed condition was met, such as the delivery of a product. CardaPay mentions decentralized arbitration systems to resolve possible disputes.

Because, unfortunately, putting a transaction on a blockchain does not automatically turn buyers and sellers into reasonable human beings. When both sides insist they are right, someone — a person, a contract, or an arbitration system — still has to decide what happens to the money.

Why build it on Cardano?

Cardano has several features that could provide a foundation for this type of solution.

The network can register and transfer ADA and other assets directly through its ledger. These native assets do not require an additional smart contract for every basic transfer because their tracking and movement are built directly into the protocol. For a payment platform, this could make it possible to work with different assets within the same infrastructure.

CardaPay’s proposal mentions stablecoins such as DJED and USDA. A stablecoin is a digital asset designed to maintain a relatively stable value, usually linked to a currency such as the US dollar. Using them could reduce one of the biggest obstacles to paying with cryptocurrencies: volatility.

A merchant probably does not want to discover that the value of a sale changed considerably while they were wrapping the package.

However, accepting stablecoins does not automatically solve problems involving liquidity, conversion, regulation, or withdrawals into national currencies. Receiving a digital asset is one thing; paying salaries, taxes, or suppliers with it is quite another. That part of the financial bridge requires more than enthusiasm and a nice-looking wallet.

CardaPay also says it could offer payments with near-zero fees. Cardano does charge transaction fees: the minimum amount depends on protocol parameters and the size of each transaction. On top of that, any commercial platform would also have its own costs, including infrastructure, maintenance, security, audits, support, and regulatory compliance.

Blockchain may reduce part of the cost, but it has not yet discovered how to provide lawyers, servers, and customer support for free.

Cardano Already Has a Card — But It Is Not CardaPay

The idea of using Cardano-related digital assets for everyday payments does not exist only within CardaPay’s proposal.

In November 2025, EMURGO — one of Cardano’s founding entities and its commercial arm — announced a partnership with Wirex to launch the Cardano Card. The card was presented in both physical and virtual formats during the 2025 Cardano Summit and integrated into the Wirex application. Its first phase allows users to spend ADA and other digital assets through Wirex’s payment infrastructure.

The difference with CardaPay is important. With the Cardano Card, the organizations responsible are clearly identified: EMURGO drives the product, while Wirex provides the issuance, application, and payment infrastructure. Wirex also publishes information about how its cards work, conversions, and country-specific limitations.

During an ecosystem event in Rio de Janeiro, I personally saw some of those cards. That does not mean I audited how they worked or bought a coffee with one, but it does establish something fairly basic: the cards exist beyond a slide deck.

In April 2026, EMURGO also introduced SecondFi, a self-custodial platform focused on payments, savings, and other financial services. Shortly afterward, SecondFi and Wirex announced a new card designed to allow users to spend directly from their own wallets without permanently giving up control of their funds.

This does not mean CardaPay, the Cardano Card, and SecondFi are the same project, nor is there any known relationship between them. They are separate initiatives trying to solve different parts of a similar problem: how to turn digital assets into something people can use outside a wallet and in everyday life.

The fact that another team has built a card around a similar idea does not tell us anything about CardaPay’s intentions, capabilities, or progress. It simply shows that using Cardano assets for everyday payments is an idea that can, in fact, be put into practice.

The example also offers a useful point of comparison: when payment infrastructure starts becoming a real product, names, issuers, applications, terms, partners, and clearly defined responsibilities usually begin to appear.

With CardaPay, that publicly verifiable layer is not yet available.

Hydra: Speed, But Not Magic

One of the central pieces of CardaPay’s proposal is Hydra, a Layer 2 solution designed to process transactions outside the main chain while using Cardano as the underlying layer for security and settlement.

A Hydra Head works like a small shared ledger among a group of participants. They commit funds from Cardano, carry out transactions within the Head, and can later return the final result to the main chain. The system is designed to provide lower latency, greater processing capacity, and reduced costs.

You could compare it to opening an extra checkout lane at a supermarket to serve a particular group of customers more quickly. The lane is still part of the same store, but it operates separately and requires everyone responsible for it to know exactly how it works.

Because Hydra is not a red button labeled “make everything faster.”

The official documentation does not describe its limitations as minor details buried at the end of the manual. It explicitly warns that operating a node requires a deep understanding of the underlying infrastructure and that funds can be put at risk if the operator is not familiar with the implementation and how it works. Hydra can be used on mainnet with real funds, but the protocol remains under development and should be used with a clear understanding of its risks.

One particularly important documented limitation appears when native tokens are minted inside a Head. If those tokens are not burned before the Head is closed, the Head cannot be finalized normally. Funds containing those tokens may become stuck, and the documentation notes that it is still being investigated whether recovery is possible in every case.

There are also restrictions inherited directly from Cardano. For example, a unit of funds — known as a UTxO — can contain so much data that it becomes too large to fit into a transaction on the main chain. If that UTxO remains inside the Head when it closes, it may not be possible to return it to Cardano.

The network topology must also be configured in the same way across all participating nodes. If their connection lists do not match, errors may occur and the system may stop making progress correctly.

None of these conditions are unusual in Cardano development. But they are not trivial problems either when trying to build a system intended for multiple merchants, different assets, and users with little or no technical experience — exactly the audience CardaPay says it wants to serve.

So yes, integrating Hydra is technically possible. But it requires considerably more work than writing the word “Hydra” into a roadmap and waiting for thousands of transactions per second to appear through spontaneous generation.

A Particularly Ambitious Roadmap

CardaPay proposed completing the project in six months through four general stages: architecture design, alpha development, beta testing, and mainnet launch. The total requested budget was 75,000 ADA.

During that period, the project expected to develop smart contracts, an Android and iOS wallet, merchant plugins, developer tools, Hydra integration, KYC and anti-money laundering systems, user testing, documentation, and security audits.

Building each of those components is not impossible. The problem is building all of them within the same budget and timeframe.

A payment platform does more than move assets from one place to another. It also has to protect keys, prevent irreversible mistakes, detect suspicious transactions, manage disputes, provide support, work correctly across different devices, and comply with the rules of every jurisdiction in which it intends to operate.

And developing a Shopify plugin does not require exactly the same skills as building a mobile application, designing an escrow contract, implementing compliance systems, or configuring Hydra. These are different products and specialties bundled into a single proposal.

The scope looks less like a minimum viable product and more like a small financial company walking through the door with all its furniture.

What Still Cannot Be Verified

This is where the main limitation in describing CardaPay’s current status becomes clear.

The proposal states that the project would have expertise in blockchain engineering, payment systems, regulatory compliance, security, product design, and business development. It also mentions advisers and possible pilot merchants. However, it does not include the names of founders, developers, advisers, legal representatives, or participating merchants. It describes profiles and skills, but does not identify the people who supposedly have them.

In fact, the first milestone states that the main positions would need to be recruited and that their experience would then be verified through CVs and references. That leaves a reasonable question about how much of the team had actually been assembled when the proposal was submitted.

The proposer’s Catalyst profile is listed only as “adis.” Five proposals appear under that profile, and none is shown as funded.

CardaPay stated that the project would be fully open source under an MIT license and would have a GitHub repository available from the beginning. The proposal even says the repository link would be included in the application. However, that link does not appear on the Catalyst page, and during the research for this article it was not possible to locate a repository clearly connected to the project.

It was also not possible to find, among the public sources reviewed, a working demonstration, deployed contracts, downloadable applications, or verifiable tests carried out by users and merchants.

This does not mean the people behind the project are not working privately. It simply means that, from the outside, the current state of development cannot be verified.

And in an ecosystem where so much of the conversation revolves around transparency, asking for a small proof of existence should hardly be considered extravagant.

A Proposal, But Not Yet a Product

CardaPay addresses a recognizable need within the ecosystem: turning Cardano’s technical capabilities into a payment experience that an ordinary person or merchant could use without first taking an accelerated course in wallets, UTxOs, smart contracts, and Layer 2 solutions.

Its vision brings together pieces that already exist: native assets, programmable contracts, stablecoins, and scalability technologies. Several components of the proposal are technically possible.

The distance between a possible idea and a usable financial service, however, is considerable.

To move beyond the conceptual stage, CardaPay would need to show at least an identifiable team, a concrete technical architecture, public code, a functional prototype, and tests carried out with users or merchants. It would also need to explain who would take responsibility for the regulatory and operational obligations associated with a payment platform.

The rejection of the Fund 14 proposal does not necessarily determine the project’s future. CardaPay could seek funding elsewhere, reduce its scope, submit a revised proposal, or begin developing its first components independently.

What cannot be done, based on the publicly available information, is describe it as a platform that already provides all of those services.

For now, CardaPay is an ambitious vision of how payments on Cardano could work: open, global, non-custodial, and connected to digital commerce.

It is an interesting vision.

Now comes the less glamorous and more important part: building it, testing it, and showing it.

Bibliography
Project Catalyst. “CardaPay: Seamless Payments Powered by Cardano”. Proposal submitted to Fund 14, Cardano Open: Developers category. (Project Catalyst)
Project Catalyst. Public profile of proposer “adis”. (Project Catalyst)
Cardano Docs. “Native tokens”. Documentation on how native assets work on Cardano. (Cardano Docs)
Cardano Docs. “Cardano fee structure”. Documentation on how transaction fees are calculated. (Cardano Docs)
Hydra Head Protocol Documentation. “Protocol overview”. General description of how a Hydra Head works and its lifecycle. (Hydra Family)
Hydra Head Protocol Documentation. “Welcome”. Information about using Hydra on mainnet and warnings for operators. (Hydra Family)
Hydra Head Protocol Documentation. “Known issues and limitations”. Limitations involving native tokens, UTxOs, funds, and node configuration. (Hydra Family)
EMURGO. “EMURGO and Wirex Partner to Launch the First-Ever Cardano Card at the Cardano Summit 2025”. November 11, 2025. (EMURGO)
Avan-Nomayo, Osato. “Cardano’s business arm partners with Wirex to launch crypto debit card”. Yahoo Finance, November 12, 2025. (Yahoo Finance)
Wirex. Public information about its cards for digital asset payments and co-branded card programs. (Wirex)
EMURGO. “EMURGO Unveils SecondFi: The Self-Custodial Neofinance Platform Bridging Everyday Spending with Onchain Yield”. April 2026. (EMURGO)
Wirex. “SecondFi and Wirex Partner to Launch Self-Custodial Card, Putting Global Users in Full Control of Their Money”. May 2026. (Wirex)
