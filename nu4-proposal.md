Who we are
==========

[Thesis](https://thesis.co) is a cryptocurrency venture production studio. We
build products and protocols to support and protect

* Self-sovereignty
* Privacy as a human right
* Opt-in culture

Portfolio
---------

We've built a portfolio of cryptocurrency projects, backed by major investors
in the space.

1) [Fold](https://foldapp.com), an online and in-store payments and rewards
   app originally launched in 2015.
2) [Keep](https://keep.network), a data confidentiality platform for Ethereum.
   Keep enables off-chain stakers to provide provable sMPC services to smart
   contracts on the EVM.
3) [tBTC](https://tbtc.network), a bonded Bitcoin sidechain built on Keep and
   Ethereum.

We'd like to add Zcash to that list, further developing and supporting the
chain and ecosystem as a major dev fee recipient.

Our vision for Zcash
====================

Our vision for Zcash is the "privacy layer for the Internet of Money".

Today, two public chains are economically relevant: Bitcoin and Ethereum. While
both have made efforts to address privacy, they've suffered from each project's
respective direction and split focus.

Privacy on Bitcoin has focused on incremental improvements. Small-set mixers and
obfuscation on Lightning are state-of-the-art, but don't offer robust privacy
guarantees.

Unlike Bitcoin, Ethereum makes privacy experimentation by developers fairly
accessible. Unfortunately, on-chain privacy constructs are expensive and compete
with other applications of the chain for block space, and no solution has gained
significant traction.

**Zcash is well-positioned to act as the privacy layer for these chains.** By
supporting user-defined assets and encouraging bridges from other ecosystems,
Zcash can maintain relevance and drive privacy in a multi-chain world.

Our capabilities
================

Over the years, we've developed core competencies applicable to the Zcash
ecosystem.

1) Engineering — our experienced team of software engineers have built popular
   applications and infrastructure in and outside the cryptocurrency space. In
   addition to our portfolio, we've built multi-currency wallets and traditional
   and cryptocurrency payment infrastructure, contributed widely to open-source,
   and shipped to prod at Silicon Valley powerhouses.

2) Design — our design team works across the spectrum. For live examples of our
   portfolio of visual, interaction, and UX design, check out
   [ln.pizza](https://ln.pizza), [Fold](https://foldapp.com),
   [My First Bitcoin Pizza](http://myfirstbitcoinpizza.com), and the visual
   identities of [Keep](https://keep.network/) and [tBTC](https://tbtc.network).

3) Dev/Ops — our engineering team has strong operational experience. We follow
   a declarative approach to infrastructure-as-code, automating testing and
   integration heavily for a good developer experience.

   In our experience, this is often overlooked in the cryptocurrency space.
   Strong tooling and cross-client testing means easier onboarding for
   developers looking to build on Zcash.

4) Legal — we've invested to make legal a core competency, involving legal
   feedback early to inform product decisions, while gating guidance to control
   costs.

5) Business development — rather than rely heavily on marketing, we've focused
   on the network we've built in the space, growing relationships and strategic
   partnerships.

Thesis is a full-stack cryptocurrency studio, but we do have some weaknesses.

* Research. Our team implements cryptographic papers and does minor
  translational research, but we prefer to partner with researchers rather than
  produce novel research in-house.
* Marketing. While we run growth campaigns for the products we launch and
  maintain, we're still formalizing our marketing efforts. We wouldn't be a
  strong pick to directly market Zcash, instead growing the ecosystem through
  products, partnerships, and infrastructure improvements.

Potential workstream
====================

Rather than proposing a roadmap which depends on other recipients' priorities or
the price of ZEC, we'll propose a workstream that plays to our strengths and can
be adjusted based on market conditions and progress across development teams.

We'd like to prioritize

1) connecting Zcash to other chains

2) ensuring ZEC is accessible from censorship-resistant DEXs

3) moving toward the orderly deprecation of `zcashd`

To that end, we propose the following projects, the detailed planning of which
we'll defer.

tZEC v1
-------

tZEC is a Zcash sidechain anchored to Ethereum, based on our work on tBTC. The
initial version of tZEC will make use of Zcash's Flyclient improvement, the
recent addition of Blake2 in Ethereum, and t-addresses. The reliance on
t-addresses will be removed in a subsequent version.

Why?

* ZEC can be accessible via Ethereum-based decentralized exchanges, providing
  resilience to delisting on centralized exchanges.
* Zcash grant recipients can use Ethereum to hedge their earnings using
  collateral-based stablecoins like MakerDAO.
* This move will continue to align the historically friendly Ethereum and Zcash
  communities, maintaining Ethereum dApp developer interest in Zcash.

Zcash Go client
---------------

The Zcash Golang client will be the third Zcash client implementation, based
on `btcd`.

Why?

* More independent implementations mean more resilience to bugs and attacks on
  the chain.
* Building a Go client will involve contributions back to the Golang crypto
  community, raising awareness of Zcash and helping grow its open-source
  presence.
* Having a Go implementation will enable easier collaboration with Ethereum
  and Cosmos developers, whose primary clients are written in Go.
* Finally, completion and a successful test period on mainnet will allow the
  safe deprecation of the C++ codebase. Ditching the remnants of the legacy
  Bitcoin codebase will make bigger protocol improvements easier across clients

User-defined assets on Zcash
----------------------------

In close partnership with the ECC and ZF, we'd like to bring user-defined
assets (UDA) to Zcash.

Why?

* User-defined assets will afford stablecoins, Bitcoin, and other digital assets
  the same privacy guarantees as ZEC.
* Many assets on the same network will increase Zcash utilization and grow the
  anonymity set.

tZEC v2
-------

The second version of tZEC will focus on a bi-directional bridge between
Ethereum-based assets and UDA on Zcash, and remove use of t-addresses.

Why?

* Bitcoin on Zcash will be possible via tBTC
* Decentralized and fiat-backed stablecoins will become usable on Zcash
* Obsoleting t-addresses will increase shielded adoption

Cosmos pegged zone
------------------

The Ethereum / Zcash bridge can be generalized and extended to operate on
the Cosmos network, lowering the cost of future interoperability work and
ensuring that Zcash is the privacy choice for the budding Cosmos ecosystem.

Why?

* As Cosmos launches IBC, each supported chain will increase the number of
  assets that can be shielded on Zcash

Budget
======

To devote significant resources and attention to Zcash over other opportunities,
we'd like to receive 25% of the dev fee.

In exchange, we'll organize a new business unit, focused on Zcash development
and following the workstream above, as well as priorities agreed upon with other
dev fee recipients and the Zcash Foundation, when appropriate.

We'll target a 20% minimum margin on our work, ensuring we have enough profit
to smoothly respond to changes in the market, as well as upside as we drive
value to the ecosystem. This margin is in line with what a typical digital
agency or software development shop might make, versus the higher margin of
specialized engineering services typically expected in the cryptocurrency space.
We believe this low margin will be offset by the security of an ongoing
allocation and future coin appreciation.

For the life of our allocation, we'll scale the team up and down based on market
conditions and our outlook, ease of hiring and onboarding, and development
priorities.

Feedback and diligence
======================

As the first proposal of this sort that we're aware of, we welcome feedback from
the Zcash Foundation and the public.

Some diligence, however, might not be appropriate in public forums due to
financial, competitive, or legal sensitivity. In those situations, we welcome
the Zcash Foundation to do diligence for the entire community, and are prepared
to share further operating details they believe are relevant.
