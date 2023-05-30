# Dynamic Collage NFT

## Overview

The Dynamic Collage NFT project combines the functionality of an ERC20 token named Collage and a Collage NFT. When purchasing Collage tokens, a dynamic Collage NFT is automatically minted and associated with the buyer's wallet. The Collage tokens are then streamed to the wallet at a rate of 1 token per second until the full purchased amount is received. The Collage NFT's appearance changes over time, with its color changing every second during the streaming process, and its size growing based on the number of Collage tokens held.

Every purchaser of Collage tokens becomes a member of the Collaging DAO, a decentralized autonomous organization. As a member, you have the opportunity to actively participate in the project by submitting new NFT designs and voting on which designs should be implemented. Ownership of Collage tokens and Collage NFTs token-gates access to the Collaging DAO's Discord community, creating a vibrant ecosystem of engaged participants.

The project also includes a website that showcases the evolving Collage NFTs in a collage-like image, creating a visually stunning display of the community's collective creativity.

## Features

- Purchase Collage tokens and receive a dynamic Collage NFT that changes color and grows in size.
- Stream Collage tokens to your wallet at a rate of 1 token per second.
- Update your stream by purchasing more Collage tokens, selling them, or transferring them to others.
- Participate in the Collaging DAO by submitting new NFT designs and voting on which designs to implement.
- Access the Collaging DAO's Discord community, token-gated based on ownership of Collage tokens and Collage NFTs.
- Collage website displays all the NFTs side by side, forming an evolving image.

## Superfluid Integration

The project leverages Superfluid, a smart contract framework that introduces the concept of Super Tokens. Super Tokens extend the functionality of basic ERC20 tokens and allow for more advanced features, such as constant flow agreements (CFAs) for streaming tokens. By integrating Superfluid, the Dynamic Collage NFT project enables the streaming functionality of Collage tokens.

For more information on Superfluid, refer to the [Superfluid Protocol Overview](https://docs.superfluid.finance/superfluid/protocol-overview/in-depth-overview).

## Tools Used

The Dynamic Collage NFT project utilizes the following tools and technologies:

- **Superfluid**: Smart contract framework for streaming Collage tokens.
- **Snapshot**: On-chain voting platform for the Collaging DAO to vote on new NFT designs.
- **Discord**: Community platform with token-gated access based on ownership of Collage tokens and Collage NFTs.
- **Future Database (suggested)**: A database to store and retrieve information related to NFT designs, voting history, and other relevant project data.

## Submit New NFT + Collage Design

As a member of the Collaging DAO, you have the opportunity to contribute to the project's creative vision by submitting new NFT designs. To submit a new design, follow these steps:

1. Create your unique NFT design using your preferred graphics software.
2. Save the design in a suitable image format (e.g., PNG, JPEG).
3. Join the Collaging DAO's Discord community and navigate to the designated channel for NFT design submissions.
4. Share your design with the community, including a brief description or concept behind the design.

Once submitted, your NFT design will be considered for implementation in future voting cycles.

## Voting on New Designs

The Collaging DAO conducts regular voting cycles to determine which new NFT designs will be implemented. The voting process occurs every 30 days and involves the following steps:

1. A designated voting period is announced in the Collaging DAO's Discord community.
2. The community members review and discuss the submitted NFT designs.
3. A voting proposal is created on the Snapshot platform, including all eligible NFT designs for consideration.
4. Community members who hold Collage tokens and Collage NFTs can cast their votes on the Snapshot platform.
5. The voting period concludes after a specified duration, typically lasting a few days.
6. The votes are tallied, and the winning NFT design(s) with the highest number of votes are selected for implementation.

By participating in the voting process, you have a direct say in shaping the Collage NFT collection and contributing to the project's evolution.

Please note that the voting process is conducted on-chain using the Snapshot platform, ensuring transparency and immutability of the voting results.

## Challenges Faced

Creating a decentralized and autonomous project from scratch poses various challenges. Some of the key challenges encountered during the development of the Dynamic Collage NFT project include:

1. **Implementing DAO Governance**: Establishing a robust governance structure within the project required careful consideration and integration of suitable DAO platforms. Finding the right balance between decentralization, security, and usability was a significant challenge.

2. **Enabling Voting and Decision-making**: Designing and implementing a fair and transparent voting system for NFT metadata updates involved creating smart contracts or integrating off-chain solutions. Ensuring the security and integrity of the voting process while providing an accessible user interface was a complex task.

3. **Integrating Superfluid on Fantom DAG**: Integrating the Superfluid protocol on the Fantom DAG (Directed Acyclic Graph) presented technical challenges. Adapting and modifying the protocol to be compatible with Fantom's specific architecture and consensus mechanism required careful consideration and extensive testing.

4. **Maintaining Collage Website**: Developing a website that displays the evolving NFTs as a collage required designing an intuitive user interface and implementing dynamic image generation. Ensuring the smooth integration of the NFT metadata updates with the website's functionality posed additional challenges.

Overcoming these challenges required thorough research, collaboration with the developer community, and meticulous testing to ensure a decentralized and autonomous project with a seamless user experience.
