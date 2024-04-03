_Editorial Comments on "The MetaLeX Whitepaper"_
_Sol Irvine, 2024-03-29_

I took the notes below during a careful reading of the whitepaper. I like the paper's call to action, and it deserves to be read in its original language. I've tried to capture the essence of the paper's thesis in my notes, but I encourage you to read [the original document](https://metalex.substack.com/p/the-metalex-whitepaper).

- My primary takeaway from the whitepaper is that much of the legal mumbo-jumbo in corporate governance can be replaced by deterministic smart contracts whose scope is carefully tailored to allow human beings to act on behalf of the organization with hard limits on their discretion. However, a purely deterministic organization is not desirable, since the organization and its individual participants operate inside one or more legal regimes that cannot be ignored.

- This thesis will resonate most with anyone who has had to slog through fundraising, setting up an ESOP, setting up a JV or acquisition, or any other significant corporate event. In my experience, the legal documents involved in these tasks are full of dubious logic puzzles, webs of cross-references, and unexplained references to extrinsic sources. An unintiated reader has no hope of understanding these documents without a lawyer's help, which sets up an unhealthy dependency on the lawyer's continued involvement. In other words, there is a powerful incentive for lawyers to keep the documents as complex and confusing as possible.

- As an experienced transactional lawyer and software developer, I've developed over the years some "hot takes" that align pretty well with the thesis of this whitepaper:

  - Most contracts are fundamentally documenting rules for moving money around. Financial rememdies and the timing of money transfers are where the rubber meets the road. Everything else is just wheelspinning, or documenting context for anticipated disputes, at best.

  - Most contract don't parse—i.e., they don't have a clear, deterministic outcome for the most anticipated and important inputs. Defined terms/taxonomy in contract language is often imprecise and open to interpretation in ways that code can never be.

  - Most clients want to know that they're getting comparable terms to what everyone else is getting, regardless of the quality or integrity of that outcome. The treat parity with their peers as a proxy for fairness and integrity of the contract terms.

  - The most-asked question by clients (in my experience) is "what's standard"? Most lawyers respond to this question based on dubious anecdotal evidence—i.e., their experience and the experience of whichever of their peers responded to a mass email query. There are major structural hurdles to compiling and sharing data about what's "standard" in a given industry or transaction type.

- There's a long history of "computational contracts" in academic circles. None of these efforts has succeeded, in my opinion. The fundamental problem is three-fold: 
  
  - Disrupting client expectations about what a contract can be, and moving them away from seeking peer parity.

  - Cultivating a community of lawyers who are willing to engage in this kind of work, and who don't lazily fall back into broken-but-familiar patterns.

  - Re-aligning lawyer incentives away from "make-work" outputs that keep them in the business of charging hourly rates for endless consultations.

- The whitepaper presents a compelling opportunity in the context of the crypto economy, where displacement of traditional methodologies through the disruptive force of deterministic code is already welcomed and expected.

# Summary of the Whitepaper

## Intro

- BORGs are traditional entities (corporations, limited liability companies, foundations, etc.) that legally mandate the use of autonomous technologies (such as smart contracts and AI) to conduct some or all of their operations and/or governance.

- Hybrid code/law solutions should be guided by the following design principles:

  - Maximize the role of trust-minimized smart contracts and other autonomous or decentralized technologies to handle as many deterministic functions as possible.

  - Minimize the role of human discretion and interpretation in the execution of smart contracts and other autonomous or decentralized technologies.

  - Identify edge-cases that may lead to unacceptably unfair, unjust, or unanticipated results and use extrinsic legal mechanisms to ensure that autonomous code is not outcome-determinative in these particular circumstances.

  - Use the existing tools of extrinsic legal regimes to hold accountable trusted human actors who are empowered to halt or influence the outcomes of autonomous technologies.

- In general a BORG should rely on strict code deference, with only narrowly-defined exceptions. 

  - A general preference for code deference can be expressed and made binding via articles of incorporation of a legal entity.
  
  - Strict code deference can result in unintended, negative consequences. 
  
    - Code can become broken or unworkable as a result of externalities that are difficult or impossible to anticipate. Changes to the underlying infrastructure or compute layer may cause application code to halt, or give intended results.
    
  - Where unintended consequences are likely, the BORG should rely on human intervention to resolve disputes and to ensure that the outcomes of autonomous technologies are fair and just.

    - The BORG should first revert to intervention by trusted human delegates.
    
    - If the trusted human delegates fail in their duties, the extrinsic legal systems governing those actors should control, as needed.

  - The rules for selection, qualification, and conduct of human delegates cannot adequately be expressed as executable code.
  
    - For example, the requirement that a human delegate adhere to confidentiality obligations is not something that can be enforced by code alone. 
  
    - Laws and regulations that govern fiduciaries, directors/officers, accredited investor rules, and similar requirements from the extrinsic legal regime should be imported via the formation documents of the BORG's legal entity.

## Phase 1

- Phase 1 of MetaLeX’s mission is to create a BORG protocol that can be used by anyone for governance and operaiton of any entity.

  - Legal doc templates and the entities that can be formed with them.

  - Smart contracts that match these legal docs and entities, on the one hand, and any adjacent protocols (including DAOs and their DeFi protocols), on the other hand.

  - A user-friendly interface bringing all BORG and DAO participants together to easily monitor and interact with the BORG.

### Phase 1A

- Phase 1A is to focus on DAO-adjacent BORGs.

  - For multisig participants, BORGs bring limited liability, clarity of purpose, the ability to easily act in the real-world (create bank accounts etc.) and in some cases other protections, such as contingent anonymity.

  - For DAOs, BORGs bring improved regulatory outcomes (as the DAO itself no longer needs to engage in business-like activities that are subject to regulations, and can instead locate these in BORGs which are able to comply with such regulations) and improved transparency and accountability of multisig members and other project contributors.

  - Since DAOs presently delegate authority to working groups, emergency councils, and other ad hoc groups, the BORG can be seen as a natural evolution and enhancement of this trend.

  - A critical aspect of the DAO-adjacent BORG is the UI presented to DAO participants. This UI should be user-friendly and should provide a clear and easy-to-understand view of the BORG’s operations and governance, as well as the rules that govern specific actions that can be take via the UI.

  - Currently, the SAFE multisig UI is the primary interface for DAO participants. Since the focus is on functional control over SAFE smart account funds, the UI provides no affordance for DAO-specific governance context.

  - Examples of DAO-specific context in the UI include:

    - Ability of multisig signers to remove themselves.
    - Limits on the BORG's ability to distribute multisig funds (timebound, amount bound, etc.)
    - Veto power of multisig signers over certain actions.
    - Appointment of an Emergency Supervisor who can seek legal remedies against non-compliant BORG member.
    - Adjustment to multisig signers' compensation.

### Phase 1B

- Phase 1B "takes traditional business entities—for example, a venture-capital-backed startup—and supercharges with them autonomous technologies to upgrade their governance, operations, financing and dealmaking capabilities for the cybernetic economy."

  - "...linked with 'real-world-assets' aka RWAs (i.e., mostly tokenized securities), since the equivalent of a DAO-token that has governance and economic powers over a DAO is a tokenized share of stock (or, in some cases, a tokenized bond/debt security) that has governance and economic rights over a bizBORG"

  - "The point is not just to slap tokenization onto existing corporate logic, but to harness these new capabilities to upgrade the corporate form for the cybernetic economy."

  - Consider the following features of current approaches to tokenized securities, and the whitepaper's responses to each:

    - Feature: Optimize liquidity and ease the burden of cap table management.
      
      - Response: Valid concerns, but essentially administrative "nice to have" features that underutilize the potential of tokenized securities.

    - Feature: Centralization of control over tokenized securities. Justified as necessary because securities derive from a trust-based legal system, and legal compliance requires trust-based interventions.

      - Response: The most important and innovative aspect of crypto technology is trust minimization. Tokenization of securities should be used to limit censorability, reversibility and permissioning, not to make them easier.

    - Feature: Not optimized to enhance disintermediation, governance, and deal-making capabilities.

      - Response: Sacrificing these qualities eliminates the most important ‘unlocks’ of putting securities on-chain.

    - Feature: Custodial control over the RWAs is often placed in a centralized trust (e.g., public benefit corp).

      - Response: DAO participants have insufficient direct influence and remedies against these trusted entities. The trusted entities are likely unable to handle insolvency or regulatory attacks in the best interests of DAO membership.
  
  - Concrete examples of how tokenized securities can enhance traditional corporate governance:
  
    - Programmatic corporate finance capabilities—e.g., the “liquidation waterfall” contemplated in complex preferred stock or mezzanine debt terms—can be trustlessly embedded in the smart contracts governing the tokenized securities, and executed without further human intervention.

    - A lead investor’s right to approve the next financing can literally preclude the corporation from issuing more stock unless that vote was registered on-chain.

    - When a company is ready to IPO, embedded issuance and transfer restrictions tied to zk-based-accreditation credentials can be switched off via a combined directors-multisig/tokenized shares vote to make the shares freely transferable.

  ## Phase 2

  - Phase 2 is establishing consensus on a protocol and accompanying ecosystem for gradual displacement of antiquated and "comically inefficient" contract and corporate governance processes.

  - In simple transactions among cryptonatives, there is a shocking lack of ‘dogfooding’. Examples:

    - "Many token lockups are ‘handshake deals’ or utilize third-party institutional custodians rather than smart-contract-based escrows."

    - "Project founders or DAO workers often make public commitments not to sell tokens, yet their users and investors do not insist that they trust-minimize this promise with smart contract lockups to prevent dumping."

  - Phase 2 introduces the term "deal technology" which means establishment of interoperable BORGs that can be composed to fit the needs of any transaction or organization.


  ## Phase 3

  - Phase 3 is establishing a legal regime that does not derive from state powers.

  - This is an extension of the self-sovereign ethos of crypto.

    - Bitcoin = self-sovereign money.

    - Ethereum = self-sovereign finance.

    - MetaLeX = self-sovereign law.
  
  - Crypto builders and users don't want to accept a strict version of 'code is law'.

    - "...many issues in crypto are not solved by the tech alone, and tend to involve the same kinds of disputes and issues of evidence, adjudication, fairness, judgment, precedent, balancing-of-the-equities, and the meting of punishments and remedies that are found in legal disputes."

  - Censorship resistance is a key feature of the crypto ethos and is threatened by reversion to state-based legal regimes.

    - "...building censorship, reversibility, and KYC/AML into our protocols and handing that control over those functions to old or new rent-seeking, government-licensed intermediaries would threaten to make autonomous code an agent or instrumentality of nation-states and their various largely unaccountable bureaucracies."

  - Phase 3 starts with "digital jurisprudence", and gradually builds out a legal regime that governs other kinds of decentralized systems—e.g., network states that are not tied to geographic boundaries, etc.