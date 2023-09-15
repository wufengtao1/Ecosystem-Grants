# ChainIDE + Polkaholic.io WASM Contract Explorer Integration Milestone 2

- **Team Name:** ChainIDE + Colorful Notion
- **Payment Address:** ChainIDE [15kdvsU1PnKCH9ShJ52cpiJmtmhSio4cPxwQK1pXgLrUGVSs](https://polkaholic.io/account/5GpLnYCwY13iqcSBLRycgZUd39ho2VWUKUCv9iqB8Fpx61QU?group=overview&chainfilters=all) + Colorful Notion [121Rs6fKm8nguHnvPfG1Cq3ctFuNAVZGRmghwkJwHpKxKjbx](https://polkaholic.io/account/DakP5k8XiY9DQbrCj23xdaUBEBxGrpJoenyB7bYDXWvtZbN?group=overview&chainfilters=all)

## Project Overview :page_facing_up:

### Overview

[ChainIDE](https://chainide.com/) is a development environment for EVM Contracts being extended to include WASM Contract templates. See [this video link](https://www.dropbox.com/scl/fi/tf0jgxsmss5b52uk0nbw7/Astar-ChainIDE-M2-New.mp4?rlkey=ts3tpvzvxpbfg7wrl7f4va1yl&dl=0) ([Testnet url](https://staging-9589904a8a.chainide.com/s/dashboard/projects)) for a full demonstration of ChainIDE's usage for EVM + WASM Contract Development.

[Polkaholic.io](https://polkaholic.io/), developed by Colorful Notion, is a multichain block explorer for the Substrate ecosystem covering 75+ chains, including parachains Astar/Shiden + Amplitude/Pendulum. Data from Polkaholic is exposed in substrate-etl's "contracts" dataset. See [this link](https://analytics.polkaholic.io/superset/dashboard/021154ed-efe1-4538-a177-30ae5ef59911/) for a PoC of Polkaholic's WASM Contract Explorer.

In Remix and other EVM IDEs, EVM developers get a well-integrated experience where newly developed Solidity contracts can be:

1. posted ABI posted publicly so that others may also read/write to the contract
2. have code verified and posted publicly
3. have block explorers use 1+2 to show contract call decoding

These 2 teams propose to provide the above well-integrated EVM development for WASM Contract Developers for all Substrate chains using the *contracts* pallet. [Initial milestones](https://github.com/use-inkubator/Ecosystem-Grants/blob/master/applications/chainide-polkaholic-integrated-wasm-contract-explorer-integration.md) by ChainIDE to cover WASM Contracts have been completed while Colorful Notion has done the groundwork to decode+index WASM Contracts. Due to the proposal of 'cargo contract build --verifiable,' this requires additional development effort from us. We have decided to apply for Milestone 2 in order to support the 'cargo contract build --verifiable' feature on ChainIDE and Polkaholic, and provide more features for wasm developers.

## Team :busts_in_silhouette:

### Key Team members

- Colorful Notion: Sourabh Niyogi + Michael Chung
- ChainIDE:
    - Xiao Wu, Founder of ChainIDE: [https://www.linkedin.com/in/%E5%95%B8-%E5%90%B4-4727237a/?locale=en_US](https://www.linkedin.com/in/%E5%95%B8-%E5%90%B4-4727237a/?locale=en_US)
    - Tim Zhang, Co-founder and CTO of ChainIDE, former Amazon star employee: [https://www.linkedin.com/in/timzmatrixlabs/](https://www.linkedin.com/in/timzmatrixlabs/)
    - Alvin Sun, Chief Scientific Officer, CBC(Canadian Blockchain Consortium) Web3 Committee Member: [https://www.linkedin.com/in/xinyao-alvin-sun/](https://www.linkedin.com/in/xinyao-alvin-sun/)
    - Jerry Zhang, Product Manager: [https://www.linkedin.com/in/jerry-zhang-5a8820220/](https://www.linkedin.com/in/jerry-zhang-5a8820220/)
    - Leon Liu, Project Managerhttps://[www.linkedin.com/in/leon-liu-b4a379117/](http://www.linkedin.com/in/leon-liu-b4a379117/)

### Contact

- **Contact Name:** Sourabh Niyogi
- **Contact Email:** [sourabh@colorfulnotion.com](mailto:sourabh@colorfulnotion.com)
- **Website** [https://polkaholic.io/](https://polkaholic.io/)

### Legal Structure

Colorful Notion:

- **Registered Address:** 55 E Third Ave San Mateo, CA 94401
- **Registered Legal Entity:** Colorful Notion, Inc. Colorful Notion is a multichain analytics company focused on L1/L2 Substrate+EVM Chains and bridges. Founded in 2021, our approach has been heavily guided by Substrate's numerous key innovations (XCM, WASM+EVM) which we embed in our key projects Polkaholic.io, XCMGAR and Substrate-etl.

ChainIDE:

- **Registered Address:** Vistra Corporate Services Centre, Wickhams Cay II, Road Town, Tortola, VG1110, British Virgin Islands
- **Registered Legal Entity:** Matrix Global Inc. ChainIDE is a multi-chain tooling platform that provides one-stop development services for blockchain developers. By providing cloud-based user experiences, ChainIDE enables users to immediately begin developing decentralized applications with no configuration, without any pre-installation or requirements on their local system. It is designed to streamline the development process by providing a user-friendly interface and a suite of tools and services to help developers write, test, and deploy smart contracts and dApps.

### Team's experience

ChainIDE was founded in 2017. Our team has been working in the blockchain field for more than five years. The core members have a combined experience of more than ten years in computing science and more than five years in blockchain development experiments. Additionally, we have over 30 product developers and a research and development team comprising ten senior engineers to ensure our services and products' effective and high-quality delivery.

Colorful Notion is led by Sourabh Niyogi and Michael Chung who have been active in blockchain engineering since 2017. Key engineers Sourabh Niyogi and Michael Chung have developed [Polkaholic.io](http://polkaholic.io/) since the Fall of 2021. Prior to building [Polkaholic.io](http://polkaholic.io/), Sourabh and Michael worked in decentralized social networking protocol development + privacy-preserving contact tracing (Wolk), mobile advertising real-time bidding algorithm design and analytics (CrossChannel/MdotM). Sourabh has founded social + web advertising startups (Social Media Networks) in SF Bay and spent time doing computational cognitive science and machine vision research at MIT. Michael hails from UC Berkeley. In the last year, Colorful Notion has worked closely with Parity Data on substrate-etl, many parachains with XCM GAR, and with many substrate parachains on [polkaholic.io](http://polkaholic.io/). Colorful Notion is a member of Astar's dapps staking Program.

### Team Code Repos

[Colorful Notion](https://github.com/colorfulnotion)

- [polkaholic](https://github.com/colorfulnotion/polkaholic)
- [substrate-etl](https://github.com/colorfulnotion/substrate-etl)

[ChainIDE](http://chainide.com)

- [plugin](https://github.com/WhiteMatrixTech/chainide-plugin-doc)

## Development Status :open_book:

ChainIDE has completed the following chain-related functionalities

- Astar Collator Node Sandbox
- Swanky Sandbox (Swanky Suite) & EVM Sandbox
- "One-click Start" of the Swanky Node Sandbox
- Built-in Wallet (Polkadot{.js}, SubWallet, Math Wallet, and Talisman) Plugin
- Wallet Panel (Network Connect，Account Management)
- Contract Deployment Panel
- Deployed Contract Interaction Panel
- Support “Import Deployed Contract” & “Use On-Chain Contract Code”
- The "ChainIDE" section in "[Key integration points.](https://github.com/use-inkubator/Ecosystem-Grants/blob/master/applications/chainide-polkaholic-integrated-wasm-contract-explorer-integration.md?plain=1#L110)”

Colorful Notion xxxxxxxxxx

- 

## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration:** 3 month
- **Full-Time Equivalent (FTE):** 2
- **Total Costs:** 120,000 USD Total: 60,000 USD (Colorful Notion), 60,000 USD (ChainIDE)

### Milestone 2 Example — Basic functionality

- **Estimated duration:** 3 month
- **FTE:** 2
- **Costs:** 120,000 USD

> :exclamation: The default deliverables 0a-0d below are mandatory for all milestones, and deliverable 0e at least for the last one.
> 

| Number | Deliverable | Specification |
| --- | --- | --- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an article/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate module: Y | The Y Substrate module will... |
| 3. | Substrate module: Z | The Z Substrate module will... |
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 5. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 6. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will... |

Key integration points:

1. [ChainIDE] ChainIDE will support  https://github.com/paritytech/cargo-contract/releases/tag/v4.0.0-alpha official version and collaborate with Polkaholic to provide support for 'cargo contract build --verifiable': After users use 'cargo contract build --verifiable,' they can submit contract for verification with a one-click process using **ChainIDE's Polkaholicscan Contract Verifier graphical plugin**. 

![](https://raw.githubusercontent.com/wufengtao1/gtants-img/main/20230915172826.png)

1. [Colorful Notion] Polkaholic will verify the verifiable code submitted through ChainIDE.
2. [ChainIDE] ChainIDE will offer the 'Open in ChainIDE' feature: For contracts/codehashes already verified on Polkaholic, users can enter the ChainIDE editing page by clicking the 'Open: ChainIDE' button, with the source code displayed on the left side.

![](https://raw.githubusercontent.com/wufengtao1/gtants-img/main/20230915172717.png)

![](https://raw.githubusercontent.com/wufengtao1/gtants-img/main/20230915172912.png)

1. [Colorful Notion] Polkaholic will provide adaptation support for 'Open: ChainIDE.'
2. [ChainIDE] When users deploy contracts using an On-Chain CodeHash and input the CodeHash, ChainIDE will automatically check with Polkaholic to see if the CodeHash has already been verified (Polkaholic provides the relevant API). If it has been verified, the package name and ABI will be automatically filled in, eliminating the need for users to manually input parameters for deployment.

![](https://raw.githubusercontent.com/wufengtao1/gtants-img/main/20230915173013.png)

1. [Colorful Notion] Polkaholic will provide relevant APIs, allowing ChainIDE to retrieve Contract Name and ABI information for already verified CodeHash through this API.
2. Colorful Notion will operate a dedicated Polkaholic Matrix room, ChainIDE will operate a Discord & telegram channel to answer the developer's questions .

## Future Plans

Please include here if you have a future plan after building this template in making it in to production.

## Additional Information :heavy_plus_sign:

**How did you hear about the Bounty Program?** Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
