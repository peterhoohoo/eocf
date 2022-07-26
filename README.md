EOCF, a crowdfunding platform hosted by EOS smart contracts

We found the disadvantages of traditional crowdfunding platforms:

1. Crowdfunding funds are centrally managed by the platform. There are risks of the platform going bankrupt and being regulated.
2. The project team lacks a supervision mechanism and lacks an audit of the use of funds.
3. Investors participating in crowdfunding have no incentive mechanism and are not highly motivated.
4. The work progress of the funded team is not limited.

We will use EOS smart contracts to develop a decentralized crowdfunding platform.

Fund Management Design:

Fund management is decentralized and hosted in a smart contract. After the development is completed, our team will give up the transfer authority of the smart contract hosting the funds. Give the authority to the EOS nodes for multi-signature management or black hole. Our team will not have the authority to transfer investors' funds.

Basic design:
Crowdfunding funds will be unlocked in batches depending on investor votes:

1. This is an open platform where anyone can initiate a project and seek investor support.

2. Project teams that accept crowdfunding must set the upper and lower limits of the crowdfunding amount. When the lower limit is reached, the project is deemed to be launched, and the investor's funds will be locked in the smart contract, waiting to be unlocked in batches. If the expiration date does not exceed the lower limit, the project will be considered a failed crowdfunding. It needs to be restarted and the investor can get his funds (EOS) back from the smart contract.

3. Teams that accept crowdfunding must reach the set delivery goals and apply for unlocked funds. Project funds are unlocked in batches, and all investors need to vote through smart contracts to unlock funds to the project team in batches.

3.Investor voting weight is realized through algorithm. The algorithm will find a balance of weights between large and small investors. When a certain turnout is reached, the smart contract will release funds to the project party. The algorithm formula will be fully open sourced on Github.

Innovative design:

We designed the one-time unlocking mode, which is different from the batch-based unlocking mode.

Project teams that accept crowdfunding can set up a model of working first and then receiving funds. When the project team promises to achieve the goal of X, and the investors vote to approve it, the crowdfunding funds will be released at one time.

This design is for the project team that accepts crowdfunding to make promises and products that are beneficial to investors, and after self-funding to complete the goal, a one-time vote to release all the crowdfunding funds to the project team.

This innovative design allows crowdfunding while working. With the progress and development of the project, more and more people will participate in crowdfunding, and the project team will receive more funds at one time.

Public Goods Section:
1. This is a project that one person can participate in. There is no curtain. Anyone can publish the project and accept crowdfunding. Anyone can become an investor.
2. All parts of the project involving smart contracts and algorithms will be open sourced and removed on github.

Benefits to the EOS ecosystem:

1.Smart contracts are developed and deployed in the main network. Crowdfunding EOS uses EOS as the base currency, and T contains USD on EOS.

2. This crowdfunding platform will first serve the project teams of the EOS community and help EOS projects. Improve the EOS ecological environment.Increase the usage and liquidity of EOS.
