# Version 6.0
## Create a new directory in your Github repo called v6.0 and initialize a new hardhat project.\  
## Implement a ReactJS user interface for your BasicDutchAuction.sol. The UI should enable a user to:\
Deploy a new BasicDutchAuction and specify all the parameters for its constructor.\
Look up a specific BasicDutchAuction by its address, view important information about the contract, and 
Submit a bid\  
The UI should have three sections. Feel free to use the following layouts in your app, or something similar.\
Section 1: Deployment\
Inputs:\
A textbox for each parameter in the constructor\
A button called “Deploy”\
Outputs:\
A label with the address of the newly created BasicDutchAuction\
Section 2: Look up info on an auction\
Inputs:\
A textbox for the address of a BasicDutchAction.\
A button called “Show Info”\
Outputs:\
A label for each property of the BasicDutchAction:\
Winner, if one already exists\
Constructor parameters\
Current price\
Section 3: Submit a bid\
Input: \
A textbox for the address of a BasicDutchAction.\
A textbox for the bid\
A button called “Bid”\
Outputs:\
A label indicating whether the bid was accepted as the winner or not\
Suggestions:\
You’ll not be evaluated on user experience, performance, or aesthetics. Just functionality.\
Note that this project is a web3 application, and thus should not need a server.\
You may use the following links as starting points for your implementation, but note that their ReactJS code is a lot more than what’s needed for this assignment. We suggest that you use it as an example to learn from, but that you actually implement your UI from scratch and only include the code you need from the example.\
Read: https://support.chainstack.com/hc/en-us/articles/4408642503449-Using-MetaMask-with-a-Hardhat-node\
Read: https://www.web3.university/article/how-to-build-a-react-dapp-with-hardhat-and-metamask\
You may use this starter repo: \
https://github.com/ChainShot/hardhat-ethers-react-ts-starter\
Instructions to get the app working:\
cd hardhat-ethers-react-ts-starter\
yarn install\
yarn hardhat compile\
cd frontend\
yarn install\
yarn start\
