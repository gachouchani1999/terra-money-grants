# Terra Grant Proposal Template

### **FINAL DOCUMENT MUST BE SUBMITTED IN THE FORM OF A GITHUB REPO FORMATTED IN MARKDOWN**

> 
- **Project Name:** Euclid
- **Team Name:** DecentralizedGoons
- **Payment Address:** terra13f6hr8sn69g4z6tupkstp2d4s7k2t7kvn06xdf

> ⚠️ The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.
> 

## Project Overview

If this application is in response to an RFP, please indicate this on the first line of this section.

If this is an application for a follow-up grant (the continuation of an earlier, successful Terra grant), please provide name and/or pull request of said grant on the first line of this section.

### Overview

Please provide the following:

- If the name of your project is not descriptive, a tag line (one sentence summary).
-> Euclid is aiming to be the first hub for all Web2 and Web3 games where they can be downloaded, game assets can be traded and users can sell their ‘used’ games. 


- A brief description of your project.
-> Euclid will offer NFT games a place to grow and become mainstream, while it will offer gamers the chance to really ‘own’ the games they are playing via an NFT.
If a gamer owns an NFT to the game, then they are allow to download it to their local machine and play it as much as they want. If then they feel that they do not want to ‘own’ the game anymore, then they can sell it for someone else, with a lower price than initially offered, that way the game would have cost way less for the initial gamer, and the other will do same repetitively.


- An indication of how your project relates to / integrates into Terra.
-> Euclid will launch on the Terra ecosystem due to all the protocols such as Anchor and Terraswap that can support the project and the experience of the cofounders in Terra.


- An indication of why your team is interested in creating this project.
-> We see an idea that no one has seen because everyone is following NFT gaming development that people are not really thinking where will all these games launch. We aim to be the first to do so.

### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):


- Data models / API specifications of the core functionality
-> SHA-256 hashed ids of different user wallet addresses are mapped to an API which is integrated into NFT games on our platform which allows the user to play the game only if he owns the hashed NFT on IPFS. 
-> Games are stored in centralized servers to be downloaded (that will be popular servers such as Azure or Digital Ocean) and the platform will provide the smart contract designs and APIs to integrate the addresses into all in-game assets and the ability to play the game itself. 
-> There are NFTs and NFT of NFTs , with a 1 to many relationship, where 1 NFT (the main game) is connected to multiple NFTs (in-game assets) that can be traded individually or as a whole NFT.

- An overview of the technology stack to be used
-> Rust / React Native / Python Backend / Postgres SQL / Azure Server


- Documentation of core components, protocols, architecture, etc. to be deployed
-> NFT of NFTs is a new architecture of smart contracts where one initial NFT holds multiple smaller NFTs with a 1 to many relationship. Each NFT can be traded or sold on a third party market individually or can be sold as a whole using the main NFT holding all the others. 
-> Smart Contract is designed to be able to hold a group of NFTs and even NFTs + tokens which allows more malleability over the assets of users in game.
-> Smart 


### Ecosystem Fit

Help us locate your project in the Terra landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
-> Euclid will be the first platform to hold all the NFT games being built on Terra and outside of Terra (using IBC protocol), where NFT games can build their communities and open markets for trade and selling of their assets. They will also offer their client base a more affordable way to play their games while they raise more money (rather than making their games free) to build even better, possibly AAA games.



- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
-> Target audience is game developing teams and also gamers who are looking for a safe-haven (like Steam) to play games, meet their friends and also play to earn.



- What need(s) does your project meet?
-> We meet the need of a marketplace for NFT gaming on Terra and related ecosystems. Just as Terra needs RandomEarth for NFT art, NFT games need Euclid.


- Are there any other projects similar to yours in the Terra ecosystem?
    -> The only project that looks similar is on a different ecosystem and is more than a list of NFT games than a full market and hub for NFT games to build their communities and for users to trade and sell games and in-game assets.
## Team

### Team members

- Name of team leader
-> Georges Chouchani: CEO
- Names of team members
-> Daniel Wehbe: CTO

### Contact

- **Contact Name:** Georges Chouchani   
- **Contact Email:** georgeschouchani1@gmail.com
- **Website:**

### Legal Structure

- **Registered Address:** Looking to register in Estonia after main investment.
- **Registered Legal Entity:** Looking to register in Estonia after main investment.

### Team's experience

Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful.

If anyone on your team has applied for a grant to Terra previously, please list the name of the project and legal entity here.

-> Georges Chouchani:
    - Works with Andromeda: recreating AMM markets.
    - Works with 
    - Worked on 2 NFT Projects on Terra.
    - Lead Blockchain Developer for Cosmostarter. (First Launchpad on Cosmos ecosystem)

-> Daniel Wehbe:
    - Lead blockchain developer of LunaLlamas.
    - Participated in 3 blockchain hackathons, got top 5 in one of them. 
    - Competitive Programmer (C++) at University - Runtime Terrors

### Team Code Repos

- [https://github.com/](https://github.com/)<your_organisation>
- [https://github.com/](https://github.com/)<your_organisation>/<project_1>
- [https://github.com/](https://github.com/)<your_organisation>/<project_2>

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- [https://github.com/](https://github.com/)gachouchani1999
- [https://github.com/](https://github.com/)daniel-wehbe

### Team LinkedIn Profiles (if available)

- [https://www.linkedin.com/](https://www.linkedin.com/) https://www.linkedin.com/in/georgeschouchani
- [https://www.linkedin.com/](https://www.linkedin.com/)https://www.linkedin.com/in/danielwehbe

## Development Status

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or RFP (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from Terra
- previous interface iterations, such as mock-ups and wireframes.

-> Discussed this idea with 10+ potential investors and seed funding starting end of December 2021. All investors waiting on TFL for approval before starting the project and initial TFL funds will be used directly to start initial step of the project.
-> Pitch Deck which is being presented: https://docs.google.com/presentation/d/1Aefe0JjCugIkhqZQMnZPzC8DgwsoAjbKb70mUJVOXUk/edit?usp=sharing
## Development Roadmap

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, it helps to describe *the functionality we should expect in as much detail as possible*, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Terra. We *recommend* that the scope of the work can fit within a three-month period and that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

- make sure to include a specification of your software. *Treat it as a contract*; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested *per milestone*.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> If any of your deliverables is based on somebody else's work, make sure you work and publish under the terms of the license of the respective project and that you highlight this fact in your milestone documentation and in the source code if applicable! Teams that submit others' work without attributing it will be immediately terminated.

- Milestone 1: 
-       Deadline: January 2022
-       Tasks:  Write Complete White Paper

- Milestone 2:
-       Deadline: April 2022
-       Tasks: Build Frontend and send inital smart contracts for audit

- Milestone 3: 
-       Deadline: June 2022
-       Tasks: Launch MVP + ICO

### Overview

- **Total Estimated Duration:** 6 months
- **Full-Time Equivalent (FTE):** 6 FTE (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** 25,000 USD

### Milestone 1 — Write Complete Whitepaper

- **Estimated duration:** 1 month
- **FTE:** 2
- **Costs:** 2,000 USD 

[Example Milestone Table](https://github.com/terramoney/terra-money-grants/blob/main/Untitled%20Database%20076bcbe63d9348558de4e6688af1d89e.csv)

### Milestone 2 - Build frontend + smart contracts

- **Estimated Duration:** 4 month
- **FTE:** 6
- **Costs:** 10,000 USD


### Milestone 3 - Launch MVP

- **Estimated Duration:** 2 month
- **FTE:** 6
- **Costs:** 13,000 USD

...

## Future Plans

Please include here

- Create a platform to decentralize all types of content creation and not only games (Youtube, twitch), changing the way people perceive paying and owning.

## Additional Information

**How did you hear about the Grants Program?** Terra Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.
-> Personal recommendation from Terra dev.
Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- Wheter there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.

-> As stated, investors from Tesla managers to VC funds are willing to invest in project but are willing to wait to see what TFL has to say about the idea before making the leap in seed funding for over $600K.
