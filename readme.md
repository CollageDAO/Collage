# Dynamic Collage NFT

## Overview
The Dynamic Collage NFT project combines the functionality of an ERC20 token named Collage and a Collage NFT. When purchasing Collage tokens, a dynamic Collage NFT is automatically minted and associated with the buyer's wallet. The Collage tokens are then streamed to the wallet at a rate of 1 token per second until the full purchased amount is received. The Collage NFT's appearance changes over time, with its color changing every second during the streaming process, and its size growing based on the number of Collage tokens held.

Every purchaser of Collage tokens becomes a member of the Collage DAO, a decentralized autonomous organization. As a member, you have the opportunity to actively participate in the project by submitting new NFT designs and voting on which designs should be implemented. Ownership of Collage tokens and Collage NFTs token-gates access to the Collage DAO's Discord community, creating a vibrant ecosystem of engaged participants.

The project also includes a website that showcases the evolving Collage NFTs in a collage-like image, creating a visually stunning display of the community's collective creativity. You can view our website [here](https://ipfs.io/ipfs/QmW4r6kJDh626jr8pBdcwtSVk6bSEpM8eiCKSUCJUjdQqd/).

## Features
- Purchase Collage tokens and receive a dynamic Collage NFT that changes color and grows in size.
- Stream Collage tokens to your wallet at a rate of 1 token per second.
- Update your stream by purchasing more Collage tokens, selling them, or transferring them to others.
- Participate in the Collage DAO by submitting new NFT designs and voting on which designs to implement.
- Access the Collage DAO's Discord community, token-gated based on ownership of Collage tokens and Collage NFTs.
- Collage website displays all the NFTs side by side, forming an evolving image.

## Superfluid Integration
The project leverages Superfluid, a smart contract framework that introduces the concept of Super Tokens. Super Tokens extend the functionality of basic ERC20 tokens and allow for more advanced features, such as constant flow agreements (CFAs) for streaming tokens. By integrating Superfluid, the Dynamic Collage NFT project enables the streaming functionality of Collage tokens.

For more information on Superfluid, refer to the [Superfluid Protocol Overview](https://superfluid.finance/).

## Modules

### Module A: Collage Submissions
Responsible for accepting new NFT design submissions from the Collage DAO community. Members can submit their unique NFT designs, which will be considered for implementation in future voting cycles. To submit a design, join the Collage DAO's Discord community and share your design in the designated channel.

### Module B: Voting on New Designs
Focuses on the voting process for new NFT designs. The Collage DAO conducts regular voting cycles to determine which designs will be implemented. Community members who hold Collage tokens and Collage NFTs can cast their votes on the Snapshot platform. The voting process is transparent and conducted on-chain.

### Module C: Collage Website
Involves the development and maintenance of the Collage [website](https://ipfs.io/ipfs/QmW4r6kJDh626jr8pBdcwtSVk6bSEpM8eiCKSUCJUjdQqd/). The website showcases the evolving Collage NFTs in a visually stunning collage-like image.

### Module D: NFT Revenue
Handles the auctioning of NFTs and the distribution of revenue generated from the sales. The primary goal is to ensure that the majority of the revenue goes back to the artists who created the NFTs:

- When NFTs are displayed on the Collage website, an auction feature is implemented to sell the NFTs to interested buyers.
- The revenue generated from the NFT sales is distributed as follows: 95% of the revenue goes back to the artist who created the NFT, while the Collage DAO retains 5% as a platform fee.
- The auction process is transparent and conducted on-chain, utilizing smart contracts to facilitate secure and verifiable transactions.
- The revenue distribution to the artists is automated, ensuring a seamless and efficient process.
- To participate in the auction and purchase NFTs, interested buyers can visit the Collage website and follow the instructions provided.
- The Collage website will prominently display information about the revenue distribution model, emphasizing the project's commitment to supporting and empowering artists.

## Tools Used
The Dynamic Collage NFT project utilizes the following tools and technologies:

- Superfluid: Smart contract framework for streaming Collage tokens.
- Snapshot: On-chain voting platform for the Collage DAO to vote on new NFT designs.
- Discord: Community platform with token-gated access based on ownership of Collage tokens and Collage NFTs.
- Covalent: Suite of API tools for live streaming the NFTs of all current Collage token holders on the Collage website.
- Future Database: A database to store and retrieve information related to NFT designs, voting history, and other relevant project data.

## Submit New NFT + Collage Design

As a member of the Collage DAO, you have the opportunity to contribute to the project's creative vision by submitting new NFT designs. To submit a new design, follow these steps:

1. Create your unique NFT design using your preferred graphics software.
2. Save the design in a suitable image format (e.g., PNG, JPEG).
3. Join the Collage DAO's Discord community and navigate to the designated channel for NFT design submissions.
4. Share your design with the community, including a brief description or concept behind the design.

Once submitted, your NFT design will be considered for implementation in future voting cycles.

## Voting on New Designs

Collage DAO will conduct regular voting cycles to determine which new NFT designs will be implemented. The voting process will occur monthly and involves the following steps:

1. A designated voting period is announced in the Collage DAO's Discord community.
2. The community members review and discuss the submitted NFT designs.
3. A voting proposal is created on the Snapshot platform, including all eligible NFT designs for consideration.
4. Community members who hold Collage tokens and Collage NFTs can cast their votes on the Snapshot platform.
5. The voting period concludes after a specified duration, typically lasting a few days.
6. The votes are tallied, and the winning NFT design(s) with the highest number of votes are selected for implementation.

By participating in the voting process, you have a direct say in shaping the Collage NFT collection and contributing to the project's evolution.

Please note that the voting process will be conducted on-chain using the Snapshot platform, ensuring transparency and immutability of the voting results.

## Challenges Faced

For now, Collage DAO will wait to launch until Superfluid is either forked or deployed to the Fantom network, though below will be our challenges creating a decentralized and autonomous project from scratch. Some of the key challenges we are encountering during the development of the Dynamic Collage NFT project include:

1. **Implementing DAO Governance**: Establishing a robust governance structure within the project will require careful consideration and integration of suitable DAO platforms. Finding the right balance between decentralization, security, and usability will be a challenge.

2. **Enabling Voting and Decision-making**: Designing and implementing a fair and transparent voting system for NFT metadata updates will involve creating smart contracts or integrating off-chain solutions. Ensuring the security and integrity of the voting process while providing an accessible user interface will be a complex task.

3. **Integrating Superfluid on Fantom DAG**: Integrating the Superfluid protocol into the Fantom network will require thorough testing and compatibility checks. The collaboration between the project team and Superfluid developers will be essential to address any challenges that arise during the integration process.

4. **Building a Vibrant Community**: Attracting and engaging a diverse community of artists, collectors, and enthusiasts will be crucial for the success of the project. Creating incentives, fostering active participation, and establishing clear communication channels will be ongoing efforts to build and maintain a vibrant Collage DAO community.

5. **Ensuring Scalability and User Experience**: As the project grows, ensuring scalability and optimizing the user experience will be significant challenges. Striving for seamless interactions, fast transaction processing, and minimal gas fees will be priorities for the project team.

Despite these challenges, the Collage team is committed to addressing them head-on, leveraging the expertise of the team members and collaborating with external partners as necessary. We believe that by overcoming these challenges, the Dynamic Collage NFT project will provide a unique and rewarding experience for its community members.

## Conclusion

The Dynamic Collage NFT project aims to create an innovative and engaging ecosystem that combines the functionality of Collage tokens, dynamic Collage NFTs, and a vibrant DAO community. By leveraging Superfluid, the project enables the streaming of Collage tokens and introduces a new dimension of interaction with NFTs. Through transparent voting processes and revenue distribution models, the project strives to empower artists and provide a platform for creative expression. Join the Collage DAO and be part of this exciting journey!

For more information and updates, please visit the [Dynamic Collage NFT website](https://collage-nft.com) and join the [Collage DAO Discord community](https://discord.gg/collage-dao).

