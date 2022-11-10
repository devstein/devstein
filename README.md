<!--
**devstein/devstein** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<img align="center" src="https://github-readme-stats.vercel.app/api?username=devstein&count_private=true&show_icons=true&theme=onedark" />

Hi 👋


All of these projects are made with 💙 in [Neovim](https://github.com/devstein/vim)

## [Picket](https://picketapi.com/)

Picket is a multi-chain, wallet-based identity provider.  Picket allows you to authenticate user using their wallet address and authorize them based of their token holdings (aka token gating).

The original inspiration for Picket came from the parallels between wallet ownership verification and traditional OAuth 2.0. Picket is OAuth 2.0 and OIDC compatible, but also supports emerging web3 native standard like Sign-In with Ethereum (SIWE).

https://github.com/picketapi

## [YCRM](https://ycrm.xyz/)

[YCRM](https://ycrm.xyz/) makes it simple to get in touch with YC founders for sales, research, recruiting, advice, or anything else!

Every day YCRM scrapes information from the YC Startup Directory and enhances it with the founders' contact information, like emails and social links. YCRM handles the grunt work of email validation and structuring it into a CRM-compatible format, so companies can focus on what matters to their business. YCRM has validated 5000+ founders' contact information and counting.

I built YCRM because I wanted to validate a B2B SaaS idea and needed founders to talk to. I had so much success with this approach that I took the time to turn it into a product for others to use.

## [KSOPS](https://github.com/viaduct-ai/kustomize-sops)

I love GitOps. At Viaduct, we managed all our infrastructure and applications via GitOps. We use Argo CD for Kubernetes and Terraform for AWS, but secrets were manually configured via the AWS CLI and stored in Secret Manager and 1Password.

We looked for a GitOps pattern for managing secrets and found SOPS. SOPS allowed us to store secrets in Git, but we needed a way to deploy these secrets to our K8s cluster. KSOPS was the solution. KSOPS enable us to store application secret configuration side-by-side with the rest of the application manifests.

https://github.com/viaduct-ai/kustomize-sops

## [Sparkmagic](https://github.com/jupyter-incubator/sparkmagic)

Viaduct's ML and data architecture was largely inspired by [Netflix's notebook first approach to data and machine learning engineer](https://netflixtechblog.com/notebook-innovation-591ee3221233). With Notebooks at the core of our development process, we needed a unified interface for ad-hoc and production spark jobs. Sparkmagic provided this unified interface. 

I started off as a user of Sparkmagic, but slowly became an active contributor. I ultimately became the main maintainer of Sparkmagic and have been since 2019. Sparkmagic makes it easy to interact with remote Spark clusters from your Jupyter notebook. It's used by thousands of developers and companies like [Pinterest](https://medium.com/pinterest-engineering/empowering-pinterest-data-scientists-and-machine-learning-engineers-with-pyspark-f41b0d1dd1b8), Amazon, more!

https://github.com/jupyter-incubator/sparkmagic

## [Hybrid Contents Manager](https://github.com/viaduct-ai/hybridcontents)

At [Viaduct](https://viaduct.ai/) we used [pgcontents](https://github.com/quantopian/pgcontents) exclusively for the `HybridContentsManager` and wanted to extend its functionality, so we created this fork [hybridcontents](https://github.com/viaduct-ai/hybridcontents). The `HybridContentsManager` allows you to use different content managers for different directories in Jupyterhub. For example, you can have one directory sync with S3 while another one is synced with a Amazon EFS. 

https://github.com/viaduct-ai/hybridcontents

## [Lexiconomy](https://github.com/devstein/unicode-eth)

The original **lexiconomy** was built in early 2018 and launched on the Ethereum mainnet on [March 28, 2019](https://etherscan.io/txs?a=0x05dde4609035e464f995d13221b5166080634f21&f=5). Like many other projects of its time, the **lexiconomy** was inspired by [CryptoKitties](https://www.cryptokitties.co/), which paved the way for the ERC-721 standard. The **lexiconomy** explored concepts of provable creation and ownership, composability, and token economics unlocked by the nascent NFT and web3 ecosystem.

The **lexiconomy**, true to its name, breaks language down into ownable, composable, and trade-able parts. Every letter, symbol, word, or phrase is a _lemma_ and every _lemma_ is a unique, ownable NFT. The project was intended to be provocative, absurd, and playful, much like the internet itself.

https://github.com/devstein/lexiconomy-v2

## [Unicode Ethereum Project](https://github.com/devstein/unicode-eth)

The Unicode Ethereum Project is an initiative to provide libraries and contracts for Unicode data, algorithms, and utilities for Ethereum developers.

The Unicode ETH Project was born from the challenges I faced doing string validation for the the Lexiconomy. To validate strings, I had to write my own UTF-8 decoder based off an [efficient C implementation](https://bjoern.hoehrmann.de/utf-8/decoder/dfa/). I started the Unicode ETH Project so other Solidity developers wouldn't have to do the same.

https://github.com/devstein/unicode-eth

## [pipelines](https://github.com/viaduct-ai/pipelines)

pipelines is a lightweight wrapper on Go channels for specifying dependencies between, running, and gracefully shutting down asynchronous processes. `pipelines` gives developers a intuitive way to declare dependencies amongst concurrent processes to create a **pipeline** (DAG) and a structured way to add new or modify existing functionality.

I built pipelines mostly for fun to play around with Go channels and DAG generation ideas I had, I also use pipelines in production to create a personal real-time trading bot with moderate success. pipelines was built before generics and would have been much more readable with them.

https://github.com/viaduct-ai/pipelines

## [Not Now,  Maybe Later (nnmbl)](https://nnmbl.xyz/)

Without accounting for timing, outbound recruiting wastes both candidates' and companies' time. I've been a victim of these inefficiencies as a candidate and a recruiter, so I decided to do as engineers do and build myself a solution. Not now, maybe later, or [nnmbl](https://nnmbl.xyz/) (pronounced "nimble") manages your inbound recruiting emails when you aren't looking for a new opportunity and organizes them, so they are accessible to you when you are.

nnmbl was a playground for me to experiment with new frameworks (Svelte, Supabase, Tailwind, daisyUI) and validating a new product idea as quickly as possible. nnmbl only exists as a landing page, but the ideas behind it live on in the [Shared Recruiting Co.](https://github.com/shared-recruiting-co)

https://github.com/devstein/nnmbl

## Shared Recruiting Co. (SRC)

More coming soon...

https://github.com/shared-recruiting-co
