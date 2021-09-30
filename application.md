# W3F Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>
> See the [Grants Program Process](https://github.com/w3f/Grants-Program/#pencil-process) on how to submit a proposal.

* **Project Name:** Expandable Substrate Module and Storage Network Compatible w/ BitBadges
* **Team Name:** BitBadges
* **Payment Address:** BTC, Ethereum (USDT/DAI) or Karura (kUSD) payment address. Please also specify the currency. (e.g. 0x8920... (DAI)) **Will need to create an address specific for BitBadges!!!**
* **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2

> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

*This isn't in response to a RFP or a request for a follow-up grant.*

### Overview

We are working on creating a storage network module on substrate compatible w/ the [BitBadges](https://bitbadges.github.io) blockchain. This will allow for substrate to interact in a meaningful way with the BitBadges ecosystem, which follows an experimental PoCP or Proof of Computation proof. 

Other projects like [Crust](https://crust.network/) or [Subspace](https://www.subspace.network/) are within the same realm of trying to create some form of storage network. The difference is how BitBadges goes about accomplishing this and what a substrate module as an integration will provide. BitBadges as a whole is working on offline-centric networks and integrating variations of distributing sharding algorithms. Their data is transmitted w/ CouchDB being an integral part of its core for node syncronization. BitBadges is also integrating w/ various third party networks viewed as either pegs or applications. 

We believe that the substrate ecosystem can provide another integration w/ our network and we might even be able to create something similar to what Crust is doing on their mainnet, but w/ BitBadges as the storage method or a mirrored peg for the data. Our team, which is currently just two people, are passionate and have years of blockchain development experience under our belts. We think Substrate can work great as one of our third party integrations or pegged chains.

### Project Details
---

Currently, we have built a variety of technologies in relation to BitBadges (1.0) for the preparation of this proposed release and its other sidechains. Among those are, building the initial [database schema](https://bitbadges.github.io/database/), and launching the MVP, getting hundreds of early users, and have migrated to a more decentralized system and our own blockchain. 

BitBadges (2.0) or BitBadges has a [paper](https://eprint.iacr.org/2021/1186) on IACR preprints introducing its architecture. Its architecture is centered around PoCP proofs i.e Proof of Computation. BitBadges is validated through synchronized nodes from those who want to host daemons, as more and more nodes are interconnected, the network becomes more and more decentralized. This allows compute through an offline-centric network, and it utilizes a variety of technologies such as the [decentralized-internet SDK](https://lonero.org/Decentralized-Internet/) and [CouchDB](https://couchdb.apache.org/) to perform this.

The use-case of BitBadges is centered around identity, specifically within the privacy-preserving realm. The first application of BitBadges was utilizing its database schema to issue badges in relation to different users on the blockchain. For permanence, BitBadges in its new form will utilize [Blake3](https://github.com/BLAKE3-team/BLAKE3) and its own blockchain for the core hashing integration. This is as opposed to IPFS which may now be looked at as potentially more of a future sidechain integration.

We believe that BitBadges will be a great fit for the Substrate ecosystem. Substrate allows for quick scalability and even the ability to easily make custom RPC calls. It also has compatibility w/ EVM or the Ethereum Virtual Machine. While BitBadges already integrates w/ rollup layers including [CloutContracts](https://cloutcontracts.net), we think an EVM integration separate from directly requiring deployments to Ethereum’s network is a plus. 

Outside of wanting to utilize the EVM module w/ substrate, we want a substrate chain for other reasons as well. We are looking to potentially deploy as a sidechain integration for expandability something like what Crust is doing w/ maxwell or its mainnet (as mentioned). We also believe that many people who want to develop or integrate w/ BitBadges may want to code in Rust, Wasm, or Solidity. 

The current UML to demonstrate the flow of BitBadges is:



The UML in regards to the substate sidechain is:
![SubstateUML](https://raw.githubusercontent.com/BitBadges/grant-application/main/assets/images/SubstateUML.png)

---

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

* Mockups/designs of any UI components
* Data models / API specifications of the core functionality
* An overview of the technology stack to be used
* Documentation of core components, protocols, architecture, etc. to be deployed
* PoC/MVP or other relevant prior work or research on the topic
* What your project is _not_ or will _not_ provide or implement
  * This is a place for you to manage expectations and to clarify any limitations that might not be obvious

### Ecosystem Fit

Currently, we have built a variety of technologies in relation to BitBadges (1.0) for the preparation of this proposed release and its other sidechains. Among those are, building the initial database schema, and launching the MVP, getting hundreds of early users, and have migrated to a more decentralized system and our own blockchain. 
BitBadges (2.0) or BitBadges has a paper on IACR preprints introducing its architecture. Its architecture is centered around PoCP proofs i.e Proof of Computation. BitBadges is validated through synchronized nodes from those who want to host daemons, as more and more nodes are interconnected, the network becomes more and more decentralized. This allows compute through an offline-centric network, and it utilizes a variety of technologies such as the decentralized-internet SDK and CouchDB to perform this.

The use-case of BitBadges is centered around identity, specifically within the privacy-preserving realm. The first application of BitBadges was utilizing its database schema to issue badges in relation to different users on the blockchain. For permanence, BitBadges in its new form will utilize Blake3 and its own blockchain for the core hashing integration. This is as opposed to IPFS which may now be looked at as potentially more of a future sidechain integration.

We believe that BitBadges will be a great fit for the Substrate ecosystem. Substrate allows for quick scalability and even the ability to easily make custom RPC calls. It also has compatibility w/ EVM or the Ethereum Virtual Machine. While BitBadges already integrates w/ rollup layers including CloutContracts, we think an EVM integration separate from directly requiring deployments to Ethereum’s network is a plus. 

Outside of wanting to utilize the EVM module w/ substrate, we want a substrate chain for other reasons as well. We are looking to potentially deploy as a sidechain integration for expandability something like what Crust is doing w/ maxwell or its mainnet (as mentioned). We also believe that many people who want to develop or integrate w/ BitBadges may want to code in Rust, Wasm, or Solidity. 

**Target Audience:**
- We are targetting developers who want to build on top of BitBadges
- Devs who use our Substrate sidechain will also be expanding the Substrate ecosystem (given its a substrate sidechain)
- This should also open up more Wasm developers and those with experience w/ Ethereum's EVM to want to do further dev work

## Team :busts_in_silhouette:

### Team members

* Andrew M. K. Nassief
* Trevor Miller

### Contact

* **Contact Name:** Andrew M. K. Nassief
* **Contact Email:** andrew@cloutpool.net
* **Website:** https://bitclout.web.app

### Legal Structure

* **Registered Address:** P.O. Box #100. Washington Township, MI 48094
* **Registered Legal Entity:** BitBadges (Becoming a sub-entity LLC.)

### Team's experience

Both members of the team have robust development experience. Trevor is currently pursuing a BS/MS dual degree and had experience developing a variety of open-source projects including BitBadges. Andrew, the team leader has years of development experience behind his belt and experience with a vast array of research accross a variety of topics. His research across a variety of industries is quite extensive.

Past experiences include work within the realms of Computational and Theoretical Physics, Quantum Engineering, and Financial Engineering. He has experimented with high performance computing in the past, and built quant trading algorithms. He also developed an obsession w/ superconductivity and Qubit processing mechanisms. He has experience contributing to the development of technology within a variety of startups.

This is the first time that this team is applying to a grant from the Web3 Foundation.

### Team Code Repos

* https://github.com/BitBadges
* https://github.com/BitBadges/bitbadgesbackend
* https://github.com/BitBadges/bitbadges.github.io

Please also provide the GitHub accounts of all team members.

* https://github.com/Mentors4EDU
* https://github.com/trevormil

## Development Status :open_book:
---

Right now in regards to the substrate sidechain, we have the initial idea planned and the BitBadges blockchain ready to start integrating sidechains. In regards to BitBadges development, we are near the final phase of BitBadges 2.0 which integrates CouchDB and its proposed offline-centric capabilities. Alot has been done such as working on the API to CouchDB integration, integrating EthAuth, doing the database migration, and having a MVP. Also, we are ...

---

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

* links to improvement proposals or [RFPs](https://github.com/w3f/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
* academic publications relevant to the problem,
* links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
* references to conversations you might have had related to this project with anyone from the Web3 Foundation,
* previous interface iterations, such as mock-ups and wireframes.

---

## Development Roadmap :nut_and_bolt:
Outside of the sidechain integration, we also want to build another expansion on Substate. This is oriented towards more of the frontend and UX phase. Phase 2 as we will call it, will be one of the applications that can be built on top of that chain. The deliverance of phase 2 will be a badges based social network centered around timestamps and issued badges within the Substate/Polkadot sidechain. 

Users will be able to load up the sidechain, connect to BitBadges core, and then issue badges to each other. Badges issued on top of the sidechain integration will appear within a nice UI. Other features such as profile, pictures, bios, etc. can all be implemented through badges. Likely, the user interface that can load all this data as well as potentially categorize/tag it, will be build w/ NodeJs + React and may integrate the Bulma CSS framework. 

**Regarding the Milestones:**

We have a specific set of tasks that will need to be completed as each phase is finished.

#### Milestone 1: Sidechain Development w/ Substrate
- Build out sidechain and work on deployment
- Different IT configurations in relation to development
- Add and integrate the EVM module (pallet)
- Create compatible chainspec file
- Create consensus layer and demo client
- Integrate contracts API and may add keyring package

#### Milestone 2: Sidechain Frontend
- Develop UI frontend
- Build w/ Node.js + React
- Consider utilizing the Bulma CSS framework
- Dockerize a sidechain + frontend package

#### Milestone 3: Social Network
- Integrate core BitBadges features
- Build off of Substrate sidechain
- Make sure network is fully responsive
- Consider making the social network modular
- Create user guide + dev guide (documentation)
- Consider making an Identity API guide
- Consider publishing plans for a secondary phase
 
The deliverables will likley be in the form of links to our code repos and a discussion (update) on our implementation. The scope of work in regards to each milestone, require a variety of different things. In regards to specification and the overview regarding the development roadmap, please turn to the overview section. For milestone #1, 

---

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

* make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md).
* include the amount of funding requested _per milestone_.
* include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
* provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
* commit to providing Dockerfiles for the delivery of your project.
* indicate milestone duration as well as number of full-time employees working on each milestone.
* **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview
---

The total we are asking for regarding development for the first initial phases, is $50k USD. This will cover costs related to deployment (hosting, potential gas fees, miscellaneous), marketing, and the whole design process. We know this may seem like much, but this is just to get the initial phases completed. Perhaps when this is expanded, further grant phases could follow to build integrations on top of this as a base. There are various considerations that go into this when looking at it through the scope of work perspective. 

---

* **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
* **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
* **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 ~ Sidechain Development w/ Substrate

* **Estimated duration:** 
* **FTE:** 
* **Costs:** $12500

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | MIT and OPNL 2.0 |
| 0b. | Documentation | Documentation on the sidechain and different modules |
| 0c. | IT Configs | Different IT configs related to the sidechain and deployment/run-time |
| 0d. | EVM Module | EVM module for Solidity compatibility and further developer onboarding |
| 0e. | Chainspec | The required chainspec file and all its different configurations |
| 1. | Contracts API | Integrate the contracts API module and contract pallet |  
| 2. | Demo Client | Build and package together a compiled demo client w/ consensus layer |  

### Milestone 2 ~ Sidechain Frontend

* **Estimated Duration:** 
* **FTE:**  
* **Costs:** $10500

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | MIT and OPNL 2.0 |
| 0b. | Documentation | Provide more details |
| 0b. | Dockerize | Provide more details |
| 1. | Develop Frontend | Provide more details |  

### Milestone 3 ~ Social Network

* **Estimated Duration:** 
* **FTE:**  
* **Costs:** $27000

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | MIT and OPNL 2.0 |
| 0b. | Documentation | Provide more details |
| 0c. | Testing Guide | Provide more details |
| 1. | Design | Provide more details |  
| 2. | Client Core | Provide more details |  

...

## Future Plans

Outside of updating dependencies and actively mantaining this project, our team has lots of plans. Many of these plans are centered around expansion in regards to our usecases and projects built around it. This will include cross-chain expansions such as TNB (TheNewBoston) and other crypto integrations as well as onboarding many developers to build on top of BitBadges and perhaps on top of its substrate sidechain as well. In regards to promotion, there are alot of things we want to do such as dev or crowdsourced innovation challenges, and focusing on constant improvement of our documentation or tutorials. BitBadges also plans on integrating a bug bounty program. We also want to focus on establishing various usecases and a large community of early adopters.

## Additional Information :heavy_plus_sign:

We heard about this grant in particular through an open grants website. We thought this matched well w/ what we are trying to do. Currently, we haven't applied for grants in the past. There is work *as mentioned* already done w/ BitBadges 2.0 and in regards to the substrate sidechain. We are also well aware of substrate's core functionality and how lots of the modules work. So far, there hasn't been anybody else who has contributed financially towards this project and we wish for careful consideration given we believe what we are developing has the potential to be massively scaled.
