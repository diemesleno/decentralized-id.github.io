---
date: 2019-03-03
title:  Web Standards and the Emerging Decentralized ID Stack
layout: single
permalink: web-standards/
canonical_url: 'https://decentralized-id.com/specs-standards/'
redirect_from: 
  - standards
  - standards/
  - specs-standards/
categories: ["Web Standards","Hyperledger Foundation"]
tags: ["Index","Credentials Community Group", "DIF","FIDO","OpenID","XDI","W3C","OASIS","JSON-LD"]
last_modified_at: 2020-04-04
---

I've begun exploring and becoming more familiar with the decentralized nature of digital identity. Open processes for standardization are critical components for enabling identification that's both decentralized and widely interoperable.

[Why Engage with Standards?](https://www.continuumloop.com/why-engage-with-standards/)
  > too many people complain about problems but don’t step to Fix It!. There are certainly a lot of flawed standards – but they make interoperability possible – not perfect – but possible. If you haven’t used them then you have no right to complain that they are too complex, too simple (even in the same standard) or too domain specific – or any of the other rants and raves that go on.
  > 
  > If you’re willing to put up with a lot of work for incremental improvements then step up and join a standard. Whether that is a (relatively) fast moving standard group like OASIS (www.oasis-open.org) or a slower but more international group like ISO you will learn. You’ll also benefit from working with experts. These experts donate their time and are more than happy to provide ideas, guidance, and leadership.

[Who Are the Identerati? - ForgeRock](https://www.forgerock.com/blog/who-are-the-identerati)
  > You’re familiar with digital identity standards like OpenID Connect, OAuth, and User-Managed Access, fundamental elements of privacy and security on the internet. But have you ever wondered how they came to be? A lot of work on these protocols went on (and goes on) behind t...

[Building Blocks for a New Architecture](https://medium.com/@trbouma/building-blocks-for-a-new-architecture-fda2238ac005)
  > After looking at the many different digital platforms and mechanisms: centralized, decentralized, proof-of-work, proof-of-stake, the list goes on, I have concluded that all of these new platforms boil down to fulfilling three core societal functions: value, identity, and status, underpinned by consensus.

## High Level Overview


* [**_A Taxonomic Approach to Understanding Emerging Blockchain Identity Management Systems_**](https://arxiv.org/pdf/1908.00929.pdf) NIST CYBERSECURITY WHITE PAPER (DRAFT) BLOCKCHAIN IDENTITY MANAGEMENT APPROACHES
JULY 9, 2019
  > Identity management systems (IDMSs) are widely used to provision user identities while managing authentication, authorization, and data sharing both within organizations as well as on the Internet more broadly. Traditional identity systems typically suffer from single points of failure, lack of interoperability, and privacy issues such as encouraging mass data collection and user tracking. Blockchain technology has the potential to support novel data ownership and governance models with built-in control and consent mechanisms, which may benefit both users and businesses by alleviating these concerns; as a result, blockchain-based IDMSs are beginning to proliferate. This work categorizes these systems into a taxonomy based on differences in architecture, governance models, and other salient features. We provide context for the taxonomy by describing related terms, emerging standards, and use cases, while highlighting relevant security and privacy considerations.

* [Hyperledger Identity Working Group - Identity Standards](https://wiki.hyperledger.org/display/IWG/Identity+Standards)

* [The Self-Sovereign Identity Stack by Oliver Terbu OSI](https://medium.com/decentralized-identity/the-self-sovereign-identity-stack-8a2cc95f2d45)

![](https://imgur.com/6MLNgXal.png)\
<sup><a href="https://www.youtube.com/watch?v=RllH91rcFdE">The Story of Open SSI Standards - Drummond Reed/Evernym SSIMeetup.org</a>[<b><a href="https://www.slideshare.net/SSIMeetup/self-sovereign-identity-ssi-open-standards-with-drummond-reed">ϟ</a></b>]</sup>


## Standards Bodies 
**_and other orgs worth keeping an eye on_**

I will begin with a listing of standards bodies, organizations and open processes, to which I'm paying attention (in addition to those previously gathered). From there, integrate and expand, as able. 

* [*Overview of Decentralized Identity Standards*](https://medium.com/decentralized-identity/overview-of-decentralized-identity-standards-f82efd9ab6c7), Nader Helmy
  > A standard, open protocol for establishing unique, private and secure connections between multiple parties without requiring the assistance of an intermediary “connection broker,” like Google, WhatsApp, an email provider, or a phone carrier. Secure connections are created by two or more peers creating and exchanging decentralized identifiers or “DIDs.” 

* [ISSA (Information Systems Security Association)](https://www.issa.org/)
* [ISAO Standards](https://www.isao.org/)
* [IETF](https://datatracker.ietf.org/wg/)
* [NIST](https://www.nist.gov/)
* [ISO](https://www.iso.org/committee/6266604/x/catalogue/p/0/u/1/w/0/d/0)
* [IEEE](https://standards.ieee.org/)
* [DIF](https://identity.foundation/working-groups/) - [GitHub](https://github.com/decentralized-identity/)
  * [Self Sovereign Identity Stack](https://medium.com/decentralized-identity/the-self-sovereign-identity-stack-8a2cc95f2d45)
* [Fido Alliance](https://fidoalliance.org/)
* [Hyperledger](https://www.hyperledger.org/join-a-group) - [Wiki](https://wiki.hyperledger.org/display/HYP/Working+Groups)
* [Kantara](https://kantarainitiative.org/groups/)	
* [OpenID](https://openid.net/wg/)
* [Sovrin](https://sovrin.org/announcing-four-sovrin-governance-framework-wg-task-forces/) - [Forum](https://forum.sovrin.org/c/working-groups)
* [Me2B Alliance](https://www.me2balliance.org/repository.html)
* [Ethereum Enterprise Alliance](https://entethalliance.org/participate/working-groups/)

{% include figure image_path="/images/1280px-Who-Runs-the-Internet-graphic.png" alt="https://es.wikipedia.org/wiki/Archivo:Who-Runs-the-Internet-graphic.png" caption="[*Internet Governance*](https://en.wikipedia.org/wiki/Internet_governance)" %}


## W3C

![](https://imgur.com/Lz6RTysl.png)

* [World Wide Web Consortium(W3C)](https://www.w3.org/) [[**T**](https://twitter.com/w3c)] [[**G**](https://github.com/w3c)]
  >The [World Wide Web Consortium (W3C)](https://www.w3.org/Consortium/) is an international community where Member organizations, a full-time staff, and the public work together to develop Web standards. Led by Web inventor and Director Tim Berners-Lee and CEO Jeffrey Jaffe, W3C's mission is to lead the Web to its full potential.
* [w3c-dvcg/w3c-dvcg.github.io</a> - Landing site for W3C Digital Verification Community Group. [<a href="https://www.w3.org/community/digital-verification/">**W**](https://sea-region.github.com/w3c-dvcg/w3c-dvcg.github.io)]
* [JSON-LD 1.0, W3C Recommendation](https://www.w3.org/TR/json-ld/)
* [W3C Workshop on Strong Authentication & Identity](https://www.w3.org/Security/strong-authentication-and-identity-workshop/report.html)

### Credentials Community Group

* [Credentials Community Group](https://www.w3.org/community/credentials/)[[**B**](https://w3c-ccg.github.io/)]  
* [Public mailing list for the Credentials Community Group](http://lists.w3.org/Archives/Public/public-credentials/) (and archives) - Anyone may read or write to this list.

#### DID the Decentralized Identifier 

<a href="https://www.w3.org/2018/vocabws/presentations/Sabadello.pdf"><img src="https://i.imgur.com/7NRcJbq.png"/></a>

* [DID Whitepaper](https://github.com/WebOfTrustInfo/rwot2-id2020/blob/master/topics-and-advance-readings/DID-Whitepaper.md)
  > A DID architecture should focus on the set of components that Mr. Gupta refers to as "the minimum required for people to be able to do business (or other critical functions) together".
  >
  >**A Decentralized Identifier (DID) Registry and Discovery Service**
  >
  > This "minimum required" is defined by a union of the proposed requirements identified by the W3C Credential Community Group, the XDI.org Registry Working Group, and the Rebooting the Web of Trust group. It consists of three functions that can be addressed by a combination of blockchain and DHT technology:
  >
  > * A DID registration function
  > * A discovery function that enables looking up a registered DID in the blockchain
  > * A master key recovery function
* [A Universally Unique IDentifier (UUID) URN Namespace](https://www.ietf.org/rfc/rfc4122.txt) <-DID's modeled after
  * [All you need to know about sequential UUID generators](https://blog.2ndquadrant.com/sequential-uuid-generators/)
* [w3c- Decentralized Identifiers (DIDs) v0.11](https://w3c-ccg.github.io/did-spec/)
* [Understanding Decentralized IDs (DIDs)](https://medium.com/@adam_14796/understanding-decentralized-ids-dids-839798b91809)
* [DID Primer](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2017/blob/master/draft-documents/did-primer.md) [[**ϟ**](https://github.com/WebOfTrustInfo/rwot7-fall2018/blob/master/topics-and-advance-readings/did-primer-extended.md)]
* [Decentralized IDentifers (DIDs)](https://www.w3.org/2018/vocabws/presentations/Sabadello.pdf) 
* [Requirements for DIDs](https://github.com/WebOfTrustInfo/ID2020DesignWorkshop/blob/master/final-documents/requirements-for-dids.pdf)
* [DIDs in DPKI](https://github.com/WebOfTrustInfo/rwot7/blob/master/topics-and-advance-readings/dids-in-dpki.md)
* [What is a DID?](https://docs.google.com/document/d/1Ym85y_bDVN9xkRZ-oD-zlUUIeZjVGWNihfZBk2GQidk/edit)
* [The Path from an id (DID) to a Real-Life Something](https://hyperonomy.com/2019/01/04/the-path-from-a-id-did-to-a-real-life-something)

<a href="https://hyperonomy.files.wordpress.com/2019/01/path-id-did-real-life-somethings-v0.2-1.png"><img src="https://hyperonomy.files.wordpress.com/2019/01/path-id-did-real-life-somethings-v0.2-1.png?w=500"/></a>

### Verifiable Credentials 

<a href="https://www.w3.org/2018/vocabws/presentations/Sabadello.pdf"><img src="https://i.imgur.com/nsZ0X7r.png"/></a>

* [Verifiable Claims Working Group](https://w3c.github.io/verifiable-claims/)
* [Verifiable Claims Data Model 1.0](https://w3c.github.io/vc-data-model/) [[**G**](https://github.com/w3c/vc-data-model)] [[**D**](https://w3c.github.io/vc-use-cases/)]
* [Verifiable Claims WG - Mailing List](https://lists.w3.org/Archives/Public/public-vc-wg/) (and archives)
* [Verifiable Credentials 101 for SSI – Tyler Ruff – Webinar 11](http://ssimeetup.org/verifiable-credentials-101-ssi-tyler-ruff-webinar-11/)


## DIF

* [Email Campaign Archive from Decentralized Identity Foundation](https://us3.campaign-archive.com/home/?u=7d1001f187a746b68d2ea0d28&id=866a6c17be)
  * [decentralized-identity/newsletter/issues/1#](https://us3.campaign-archive.com/?u=7d1001f187a746b68d2ea0d28&id=d03c08ac8b): Working Group Updates:
  * [decentralized-identity/newsletter/issues/2#](https://us3.campaign-archive.com/?u=7d1001f187a746b68d2ea0d28&id=39d596a7f0) - Working Group Updates 
  * [decentralized-identity/newsletter/issues/4#](https://us3.campaign-archive.com/?u=7d1001f187a746b68d2ea0d28&id=8efd1e4a75)
  * [decentralized-identity/newsletter/issues/5#](https://us3.campaign-archive.com/?u=7d1001f187a746b68d2ea0d28&id=3dc94cb937)

Working Group Updates:
  * ☂️ InterOp Project - Demonstrating interoperability across various teams/project and technology stack.
  * 💡 Identifiers & Discovery - How people, organizations, and devices can be identified and located without centralized systems.
  * 💠 Storage & Compute - Secure, encrypted, privacy-preserving storage and computation of data.
  * 🛡️ Claims & Credentials - Verifying claims and assertions of identities.
  * 🔓 DID Auth - DID-based authentication specs, standards, and libraries.


[Decentralized Identity & Trust Technology APAC/ASEAN Call](https://medium.com/decentralized-identity/decentralized-identity-meetings-for-the-apac-region-7221b9aad29)
> APAC and ASEAN engineers are historically under-represented in EU & US driven global efforts due to simple scheduling concerns — conference calls and other avenues of information sharing are often scheduled at inconvenient times for APAC and ASEAN participants. APAC and ASEAN engineers find it difficult to participate in communities that meet only between midnight and sunrise. This results in APAC and ASEAN solutions developing as parallels to their equivalent EU- & US-based global efforts, rather than as extensions of them or as interlocutors for them.

[DIF starts DIDComm Working Group](https://medium.com/decentralized-identity/dif-starts-didcomm-working-group-9c114d9308dc)
> Over the past few months, the DIF and Hyperledger Aries community have come together and agreed to work on a common work item aimed at developing secure communication based on Decentralized Identifiers (DIDs) — hence the name DIDComm, which is short for DID Communication. Significant prior work in developing a messaging-based communication protocol using DIDs has been incubating in the HyperLedger (HL) Aries community, with the progress of this effort evident in the resulting Aries RFCs. To address the requirements of a broader and more heterogeneous community we selected DIF as the place to pursue the next phase of work associated with this effort. Presenting the progress of DIDcomm to other relevant working groups will drive the interoperability between the various decentralized identity vendors and hence enabling a range of decentralized identity-related use cases.


### DID Auth 

![](https://imgur.com/XMaq5cil.png)


   * [DID Auth and the Little I-am-Me](https://medium.com/@markus.sabadello/did-auth-and-the-little-i-am-me-ec14d757ff09)
   * [Introduction to DID Auth](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-spring2018/blob/master/final-documents/did-auth.md) [[**ϟ**](http://ssimeetup.org/introduction-did-auth-markus-sabadello-webinar-10/)]

<a href="http://ssimeetup.org/introduction-did-auth-markus-sabadello-webinar-10/"><img src="https://i.imgur.com/YNlk8RY.png"/></a>\
http://ssimeetup.org/introduction-did-auth-markus-sabadello-webinar-10


## Decentralized Key Management-Agents 

<img src="https://i.imgur.com/0SLcjUv.png"/>

* [Decentralized Key Management (DKMS): An Essential Missing Piece of the SSI Puzzle - Drummond Reed](https://www.slideshare.net/SSIMeetup/decentralized-key-management-dkms-an-essential-missing-piece-of-the-ssi-puzzle-drummond-reed)
* [Recommendations for Decentralized Key Management Systems](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2017/blob/master/topics-and-advance-readings/dkms-recommendations.md)
* [Agent to Agent Communication](https://drive.google.com/file/d/1PHAy8dMefZG9JNg87Zi33SfKkZvUvXvx/view): Daniel Hardman explains the goals of agent to agent communication


![](https://i.imgur.com/5qc1qrG.png)\
<sup><a href="http://ssimeetup.org/decentralized-key-management-dkms-essential-missing-piece-ssi-puzzle-drummond-reed-webinar-8/">DKMS - An Essential Missing Piece of the SSI Puzzle. Drummond Reed. SSIMeetup.org</a></sup>

* [Microsoft- Decentralized Identity — Own and Control Your Identity.](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE2DjfY)
![](https://i.imgur.com/ozOLCuW.png)

## Ethereum ERC-EIP

* [ERC: Lightweight Identity #1056](https://github.com/ethereum/EIPs/issues/1056) —This ERC describes a standard for creating and updating identities with a limited use of blockchain resources. An identity can have an unlimited number of delegates and attributes associated with it. Identity creation is as simple as creating a regular key pair ethereum account, which means that it's fee (no gas costs) and all ethereum accounts are valid identities. Furthermore this ERC is fully DID compliant.
* [ERC1056 ❤ ERC780 — an open identity and claims protocol for Ethereum](https://medium.com/uport/erc1056-erc780-an-open-identity-and-claims-protocol-for-ethereum-aef7207bc744)
* [EIP-780 Ethereum Claims Registry](https://github.com/ethereum/EIPs/issues/780)
* [EIP712](https://github.com/ethereum/EIPs/blob/f29527ab39357548b06b29e937a48f06ae099de7/EIPS/eip-712.md) - This is a standard for hashing and signing of typed structured data
* [ERC-1484 Digital Identity Aggregator](https://github.com/ethereum/EIPs/issues/1495) —A protocol for aggregating digital identity information that's broadly interoperable with existing, proposed, and hypothetical future digital identity standards.
* [EIP-1078](https://github.com/ethereum/EIPs/blob/ed621645c8f3bc5756492f327cda015f35d9f8da/EIPS/eip-1078.md) - 
This presents a method to replace the usual signup/login design pattern with a minimal ethereum native scheme, that doesn’t require passwords, backing up private keys nor typing seed phrases. 
* [ERC-1077 and ERC-1078: The magic of executable signed messages](https://ethereum-magicians.org/t/erc-1077-and-erc-1078-the-magic-of-executable-signed-messages-to-login-and-do-actions/351)
* [ERC-EIP on GitHub](/blockchain/ethereum/#eip---erc) **>>**

### ERC725-735 

* [ERC725](https://github.com/ethereum/EIPs/issues/725) 
  * The following describes standard functions for a unique identifiable proxy account to be used by humans, groups, organisations, objects and machines
* [ERC735](https://github.com/ethereum/EIPs/issues/735) -  The following describes standard functions for adding, removing and holding of claims.
  - These claims can attested from third parties (issuers) or self attested.
* [Origin partners on ERC725](https://coinjournal.net/origin-protocol-partners-on-new-erc-725-alliance-to-promote-the-adoption-of-blockchain-based-identity-standard)
* [Managing Identity with a UI—ERC-725](https://medium.com/originprotocol/managing-identity-with-a-ui-for-erc-725-5c7422b38c09)
* [Ethereum ERC725 Blockchain Based, Self-Sovereign Identity Management](https://bitcoinexchangeguide.com/ethereum-erc725-blockchain-based-self-sovereign-identity-management/)
* [erc725alliance.org](https://erc725alliance.org)
* [ERC: Lightweight Identity #1056](https://github.com/ethereum/EIPs/issues/1056) —This ERC describes a standard for creating and updating identities with a limited use of blockchain resources. An identity can have an unlimited number of delegates and attributes associated with it. Identity creation is as simple as creating a regular key pair ethereum account, which means that it's fee (no gas costs) and all ethereum accounts are valid identities. Furthermore this ERC is fully DID compliant.



## Blockcerts 
* [Learning Machine](https://www.learningmachine.com/)
* [Academic Credentialing and the Blockchain](https://www.learningmachine.com/academic-credentialing-blockchain/)
* [Blockcerts](https://www.blockcerts.org), developed by learning machine is an open standard for issuing and verifying blockchain-based official records; The project offers  open-source libraries, tools, and mobile apps. MIT has [issued](https://www.insidehighered.com/news/2017/10/19/mit-introduces-digital-diplomas) digital certificates based on this standard.
  * [CXC (Carribean) Pilots E-Certificates on the Blockchain](https://www.cxc.org/cxc-pilots-e-certificates-on-the-blockchain/)
  * [A Decentralized Approach to Blockcerts Credential Revocation](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2017/blob/master/final-documents/blockcerts-revocation.md)


## Schema
* [Schema](https://schema.org) — a collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet. Schema.org vocabulary can be used with many different encodings, including RDFa, Microdata and JSON-LD. These vocabularies cover entities, relationships between entities and actions, and can easily be extended through a well-documented extension model. Over 10 million sites use Schema.org to markup their web pages and email messages. Many applications from Google, Microsoft, Pinterest, Yandex and others already use these vocabularies to power rich, extensible experiences."
