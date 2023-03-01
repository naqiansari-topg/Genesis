# Genesis Crowd Funding Application
This is a decentralized crowdfunding application built on blockchain technology using Solidity, React JS, Hardhat, and Metamask on the Goerli network. This application allows individuals or organizations to raise funds for their projects, campaigns, or businesses without the need for intermediaries such as banks, payment gateways, or crowdfunding platforms.

# How it works
- A user creates a campaign by specifying the project details, fundraising goal, and deadline for the campaign.
- The campaign is added to the blockchain as a smart contract, which holds the funds raised and enforces the rules of the campaign.
- Users can contribute to the campaign using Ether (ETH) through the Metamask wallet on the Goerli network.
- The smart contract keeps track of the funds raised and releases them to the campaign owner when the campaign reaches its fundraising goal before the deadline. If the goal is not reached, the funds are returned to the contributors.
- Campaign owners can withdraw the funds raised once the campaign is successful.

## Advantages of Crowdfunding on Blockchain
- Decentralization: This crowdfunding application is decentralized, meaning it is not controlled by any central authority or intermediary. This eliminates the risk of fraud or manipulation by third parties.

- Transparency: The transactions and activities on the blockchain are transparent and can be viewed by anyone, providing greater accountability and trust in the crowdfunding process.

- Security: The blockchain technology is secure and tamper-proof, providing a higher level of security for the funds raised.

- Lower Fees: Traditional crowdfunding platforms charge high fees for their services. With this blockchain-based crowdfunding application, there are no intermediaries, so fees are significantly lower.

- Global Access: This crowdfunding application is accessible to anyone with an internet connection, enabling global participation in fundraising campaigns.

# Installation and Deployment 

To install and deploy this application, follow these steps:

- Clone this repository
- Install the required dependencies by running npm install
- Create a .env file and add your Metamask wallet private key and Alchemy API key
- Deploy the smart contract to the Goerli network using Hardhat by running ```npx hardhat run scripts/deploy.js --network goerli```
- Start the React application by running npm start


# Usage 
To use this crowdfunding application, you will need a Metamask wallet with Goerli ETH on it. Follow these steps to use the application:

1) Connect your Metamask wallet by clicking on the Connect Wallet button in the top right corner of the application.
2) Once your wallet is connected, you can view the ongoing campaigns on the home page.
3) To contribute to a campaign, click on the campaign card and enter the amount you wish to contribute. Confirm the transaction in your Metamask wallet to complete the contribution.
4) To start a crowdfunding project, click on the Add Project button in the navigation bar.
Fill in the required information, such as project details, fundraising goal, and deadline for the campaign.
5) Click on the Create Project button to deploy your campaign on the blockchain.
You can view your ongoing campaigns on the My Campaigns page.
6) Once your campaign reaches its fundraising goal before the deadline, you can withdraw the funds raised by clicking on the Withdraw Funds button on the campaign card.

Note: Make sure you have enough Goerli ETH in your Metamask wallet to contribute to campaigns or start new ones. You can get free Goerli ETH from a Goerli ETH faucet or ask for it on a Goerli ETH testnet faucet website.