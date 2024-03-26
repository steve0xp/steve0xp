<div id="header" align="center">
  <img src="https://media.giphy.com/media/mCRJDo24UvJMA/giphy.gif" width="150"/>

<div id="badges">
  <a href="https://www.linkedin.com/in/phamsteven/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://twitter.com/steve0xp">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>

<h1>
  Welcome!
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>
</div>

## 🙋🏻‍♂️ About Me :

- 🔭 I’m a smart contract dev / dev rel currently with over three years of experience in DeFi full-time. I am currently working full-time on a number of projects (using different github accounts :)). That said, I am always open to meeting more people in the industry so please feel free to reach out to chat! Please inquire for my formal resume :), otherwise here's some details about some of my work / me!
- 🌱 As well, I contributed / contribute to open-source DeFi projects including: 
   - Smart Contract Work (Solidity): Yearn strategies && general oracle design
   - Technical Writing: [technical threads](https://typefully.com/t/T3CNVzI) for Yearn, Balancer, DAO tooling, Subgraphs, && NFTs
   - Developer Advocacy: [beginner tutorials](https://github.com/scaffold-eth/scaffold-eth-challenges/tree/challenge-4-dex) & more [advanced tutorials](https://github.com/scaffold-eth/Scaffold-ETH-DeFi-Challenges/tree/challenge-1-simple-yearn-strategy) about integrating into actual DeFi protocols for BUIDL GUIDL
      - Most recent work is focused on finishing the [Scaffold-ETH-DeFi-Challenge-2 revolving around ERC4626 Adaptors with Sommelier and Aura Protocol](https://github.com/scaffold-eth/Scaffold-ETH-DeFi-Challenges/tree/challenge-2-sommelier-erc4626-adaptor) as an example. I am also working with a handful of other developers on [Custom Balancer pool content for Scaffold-Balancer](https://medium.com/@BalancerGrants/buidlguidl-are-developing-a-how-to-for-balancer-custom-pools-from-scaffold-eth-afd7b6a55d03).  
- 👨🏻‍💻 Recent public work: Serve as a Balancer Grants Committee member, co-hosted a hackerhouse at EthDenver 2023 with Jessy's Hackerhouse && BUIDL GUIDL, core contributor to Photon, a decentralized stablecoin protocol (see pinned repos && CV Details below for highlights) 
- ⚡ Fun facts: I've hitch hiked in Iceland, and was CTO of a hockey equipment startup in the NHL (but can't stop on skates 🤷🏻‍♂️)

---
## 📜 CV - (newest to oldest, if no README see description)

1. **April 2023 - Present: Defi Smart Contracts Contributor && Dev Rel w/ numerous projects**

2. **January 2023 - April 2023: [Yearn Mellow-Gearbox_wETH Strategy](https://github.com/umphams/yearn_mellow-gearbox-strategy)**

3. **January 2023 - Present: Standardized Oracle System** - in private repo currently. 
  - Draft Thread: https://typefully.com/t/yNLqP7A
  - Figma: https://www.figma.com/file/cJnuNMpZaU7qto39P8NxR2/Today%27s-Oracle-Design-Flow-Chart-v1?node-id=0%3A1&t=0I5QbBWpBvaO4G6M-1


4. **March 2022 - January 2023: Ekonomia Technologies core contributions to Photon Finance Protocol** - Smart Contract Development && Partnerships Integration (see [architecture schematic](https://drive.google.com/file/d/1cNvRpRHazSg40sw10evm_sVobBsfroec/view?usp=share_link) & [whitepaper](https://drive.google.com/file/d/1nWtAZnyW2famK8JDk3CNW-0Yzv_w3UFa/view?usp=share_link) here for reference. Highlighted PRs below showcase my past experience in conceptual design, implementation, reviewing, && testing for various contracts:

    - **[ModuleManager.sol](https://github.com/ekonomia-tech/protocol-alpha/pull/49)** :
      - The Module Manager acted as the intermediary between the Modules and the
Kernel.
    - **[*Genesis TWAP Oracle for stablecoin, governance token, and possibly other modules](https://github.com/ekonomia-tech/protocol-alpha/pull/44)** : 
      - Oracle exposed USD/PHO price using v1 Curve PHO/FraxBP Metapool TWAP Pair Oracle && USD PriceFeeds (USD/FRAX && USD/USDC). Initial design was an oracle aggregator w/ built in contingencies for a modular oracle system to be used throughout protocol. It was simplified to carry out an iterative design process.
    - **[PIDController.sol, Pool.sol, Share.sol inspired from Frax && wrote foundry tests mainly for PIDController.t.sol](https://github.com/ekonomia-tech/protocol-alpha/pull/11)** : 
      - Developed the initial conceptual designs of a PID Controller within stablecoin mechanism design for peg control similar to FRAX foundational tech. 
    - **[Liquity Subgraph for Reputation Scoring](https://github.com/ekonomia-tech/lending-subgraph-standard/pull/8)** : 
      - Created and deployed the first iteration of the liquity subgraph that follows the "Lending Subgraph Standard" schema. It was meant to be used for a potential reputation scoring system within early iterations of Photon protocol where lending and borrowing rates would differ based on on-chain reputation scores from accrued & ongoing on-chain activity.   
      
5. **March 2022 - [Pak Subgraph](https://github.com/squirtleDevs/subgraphs)** : Implemented my first subgraph whilst thinking about perspective & use cases of end-user.
  
6. **January 2022 - Present [BUIDL GUIDL Contributor](https://buidlguidl.com/builders/0x59ea223b48f0E1B6AdDD86cE6551dC44E2c7cb75)**

  _*TWAP implementation found not suitable for curve, so implemented other corrections. Spun out to now deeper understanding && research for a generic oracle setup for all protocols to use._
