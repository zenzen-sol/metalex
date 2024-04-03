[⇠ Top](../README.md)

# Editorial Comments on the MetaLeX Whitepaper

_Sol Irvine, 2024-03-29_

These are just some off-the-cuff observations made during [my close reading of the whitepaper](./whitepaper-summary-sli.md). 


## TL;DR

My primary takeaway from the whitepaper is that much of the legal mumbo-jumbo in corporate governance/events can be replaced by a more efficient and deterministic collection of smart contracts. However, those contracts must be carefully scoped to: 

1. Allow human beings to operate the organization inside one or more extrinsic legal regimes.
2. Provide constraints for handling the inevitable cases where unintended consequences run amok.
3. Avoid runaway complexity that would make them as opaque as the legal documents they replace.

The whitepaper presents a compelling opportunity since the crypto economy already welcomes and expects displacement of traditional methodologies through the disruptive force of deterministic code.

I like the paper's call to action. It deserves to be read in its original language. I've tried to capture the essence of the paper's thesis [in my notes](./whitepaper-summary-sli.md), but I encourage you to read [the original document](https://metalex.substack.com/p/the-metalex-whitepaper) and [its precursor blog post](https://delphilabs.medium.com/assimilating-the-borg-a-new-cryptolegal-framework-for-dao-adjacent-entities-569e54a43f83).

## Multilateral Problem

It's interesting that the MetaLeX thesis should resonate equally with:

- Anyone who has looked deeply into DAO governance and uncovered a version of traditional corporate governance (delegation to boards and committees, capture by influential personalities, etc.), but under a veneer of "decentralization".

- Anyone who has been forced to slog through fundraising, setting up an ESOP, setting up a JV or acquisition, or any other significant corporate event in a traditional corporate entity. 

### Emergent Approaches to DAO Governance Fall Short

In the crypto space, there's a history of tension between two major approaches to DAO governance: 

- Purely code-driven DAO governance, such as the classic Compound approach where proposals by participants are limited to adjustment of quantitative parameters or code changes that do not require any human judgment to implement. The problem with this approach is that every proposer and reviewer must be fluent in code.

- Open-ended DAO governance, where proposals take a narrative form and both evaluation and implementation require a significant amount of human judgment. The problem with this approach is that it's prone to capture by bad actors.

The MetaLeX whitepaper leans into a hybrid approach where more nuanced automated governance mechanisms can handle more nuanced human inputs. Because neither of the current, emergent approaches has been able to fully address the needs of DAO participants, there's a lot of apathy, disappointment, angst, and room for innovation in this space.

### TradLaw is Deeply Unwell

As an experienced transactional lawyer and coder, I've developed over the years some "hot takes" that align pretty well with the thesis of this whitepaper:

- Most contracts are fundamentally documenting rules for moving money around. Financial remedies and the timing of money transfers are where the rubber meets the road. Everything else is just wheelspinning, or documenting context for anticipated disputes, at best.

- Most contract don't parse—_i.e._, they don't have a clear, deterministic outcome for the most anticipated and important inputs. Defined terms/taxonomy in contract language is often imprecise and open to interpretation in ways that code can never be.

- Most clients want to know that they're getting comparable terms to what everyone else is getting, regardless of the quality or integrity of that outcome. The treat parity with their peers as a proxy for fairness and integrity of the contract terms.

- The most-asked question by clients (in my experience) is "what's standard"? Most lawyers respond to this question based on dubious anecdotal evidence—_i.e._, their experience and the experience of whichever of their peers responded to a mass email query. There are major structural hurdles to compiling and sharing data about what's "standard" in a given industry or transaction type.

- In my experience, the legal documents involved in corporate events are particularly prone to dubious logic puzzles, webs of cross-references, and unexplained references to extrinsic sources. An unintiated reader has no hope of understanding these documents without a lawyer's help, which sets up an unhealthy dependency on the lawyer's continued involvement. In other words, there is a powerful incentive for lawyers to keep the documents as complex and confusing as possible.

- The legal industry is firmly entrenched in a 10-year+ lag behind the rest of the economy in terms of adopting new technologies, and will remain there until it's forced to alter its business model. I worked in BigLaw long enough to get a taste for the inertia and resistance to change that emanates from senior partners whose secretaries read yesterday's email to them in the morning.

## Why Computational Contracts Went Nowhere

There's a long history of "computational contracts" in academic circles. None of these efforts has succeeded meaningfully, in my opinion. 

The fundamental problem is adoption, and there are three factors working against it: 
  
- Disrupting client expectations about what a contract can be, and moving them away from seeking peer parity.

- Cultivating a community of lawyers who are willing to engage in this kind of work, and who don't lazily fall back into broken-but-familiar patterns.

- Re-aligning lawyer incentives away from "make-work" outputs that keep them in the business of charging hourly rates for endless consultations.

## Recent Developments in the Underlying Tech

When I first started building in crypto, the Gnosis SAFE multisig was the gold standard for managing a shared on-chain account, largely because it was battle-tested and already widely adopted. That hasn't changed, although the product has rebranded to [Safe {Core}](https://safe.global/core) "smart accounts", and massively improved its UX.

Today, [Safe exposes an API](https://docs.safe.global/advanced/smart-account-overview) for developers to add "modules" that enhance the functionality of the Core smart account. This is a powerful feature that allows developers to build on top of the Safe platform.

In my experience, serious users of Safe are hesitant to adopt modules, since they potentially introduce new code risk and surface area for attacks/bugs. If MetaLeX is able to make a strong push for adoption of some standardized and vetted modules, it could go a long way toward alleviating these concerns.

In addition, there are more multisigs coming online and gathering credibility as they accrue more time without issues. Safe Core is an EVM ecosystem product. Since the MetaLeX thesis is not chain-dependent, other multisig technologies may be needed to provide a foundation in other ecosystems.

## On Branding

I think the taxonomy of "bizBORGs" vs "DAO-adjacent entities" needs to be catchier/more memorable. Adoption is with this
kind of effort, so classic marketing/branding principles apply.
