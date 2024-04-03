[⇠ Top](../README.md)

## Editorial Comments on the MetaLeX Whitepaper

_Sol Irvine, 2024-03-29_

These are just some off-the-cuff observations made during [my close reading of the whitepaper](./whitepaper-summary-sli.md). 


### TL;DR

- My primary takeaway from the whitepaper is that much of the legal mumbo-jumbo in corporate governance/events can be replaced by a more efficient and deterministic collection of smart contracts. However, those contracts must be carefully scoped to: 

  1. Allow human beings to operate the organization inside one or more extrinsic legal regimes.
  2. Provide constraints for handling the inevitable cases where unintended consequences run amok.
  3. Avoid runaway complexity that would make them as opaque as the legal documents they replace.

- The whitepaper presents a compelling opportunity since the crypto economy already welcomes and expects displacement of traditional methodologies through the disruptive force of deterministic code.

- I like the paper's call to action. It deserves to be read in its original language. I've tried to capture the essence of the paper's thesis [in my notes](./whitepaper-summary-sli.md), but I encourage you to read [the original document](https://metalex.substack.com/p/the-metalex-whitepaper) and [its precursor blog post](https://delphilabs.medium.com/assimilating-the-borg-a-new-cryptolegal-framework-for-dao-adjacent-entities-569e54a43f83).

### TradLaw is Deeply and Badly Broken

- This thesis will resonate most with anyone who has been forced to slog through fundraising, setting up an ESOP, setting up a JV or acquisition, or any other significant corporate event. In my experience, the legal documents involved in these tasks are full of dubious logic puzzles, webs of cross-references, and unexplained references to extrinsic sources. An unintiated reader has no hope of understanding these documents without a lawyer's help, which sets up an unhealthy dependency on the lawyer's continued involvement. In other words, there is a powerful incentive for lawyers to keep the documents as complex and confusing as possible.

- As an experienced transactional lawyer and software developer, I've developed over the years some "hot takes" that align pretty well with the thesis of this whitepaper:

  - Most contracts are fundamentally documenting rules for moving money around. Financial remedies and the timing of money transfers are where the rubber meets the road. Everything else is just wheelspinning, or documenting context for anticipated disputes, at best.

  - Most contract don't parse—i.e., they don't have a clear, deterministic outcome for the most anticipated and important inputs. Defined terms/taxonomy in contract language is often imprecise and open to interpretation in ways that code can never be.

  - Most clients want to know that they're getting comparable terms to what everyone else is getting, regardless of the quality or integrity of that outcome. The treat parity with their peers as a proxy for fairness and integrity of the contract terms.

  - The most-asked question by clients (in my experience) is "what's standard"? Most lawyers respond to this question based on dubious anecdotal evidence—i.e., their experience and the experience of whichever of their peers responded to a mass email query. There are major structural hurdles to compiling and sharing data about what's "standard" in a given industry or transaction type.

### Re Computational Contracts and TradLaw Approaches to Automation

- There's a long history of "computational contracts" in academic circles. None of these efforts has succeeded meaningfully, in my opinion. The fundamental problem is adoption, and there are three factors working against it: 
  
  - Disrupting client expectations about what a contract can be, and moving them away from seeking peer parity.

  - Cultivating a community of lawyers who are willing to engage in this kind of work, and who don't lazily fall back into broken-but-familiar patterns.

  - Re-aligning lawyer incentives away from "make-work" outputs that keep them in the business of charging hourly rates for endless consultations.

### Re Emergent Problems in DAO Governance

- In the crypto space, there's a history of tension between two major approaches to DAO governance: 

  - Purely code-driven DAO governance, such as the classic Compound approach where proposals by participants are limited to adjustment of quantitative parameters or code changes that do not require any human judgment to implement. The obvious problem with this approach is that every proposer must be fluent in code.

  - Open-ended DAO governance, where proposals take a narrative form and both evaluation and implementation require a significant amount of human judgment. The obvious problem with this approach is that it's prone to capture by bad actors.

- The MetaLeX whitepaper leans into a hybrid by proposing more nuanced automated governance mechanisms that can handle more nuanced human inputs than simple parameter tweaks or changes to the raw code.

- Because neither of the emergent approaches has been able to fully address the needs of DAO participants so far, there's a lot of apathy, disappointment, angst, and room for innovation in this space.

