# CREATING AN ERC-20 TOKEN
METAMASK

1. CREATE METAMASK WALLET USING THE METAMASK EXTENSION OR APP AND SAVE THE WALLET ADDRESS.
2. CONNECT TO GORELI TEST-NETWORK IN SETTINGS.
3. MINE GORELIETH USING THIS LINK (https://goerli-faucet.pk910.de/).
 
4. CLAIM 0.01 GOERLIETH OR MORE. NOW YOUR METAMASK ACCOUNT SHOULD LOOK LIKE THIS :


<img width="1440" alt="Screenshot 2023-06-29 at 4 47 59 PM" src="https://github.com/AYUSH363/BLOCKCHAIN/assets/120236457/9c0b895e-9b5c-4d23-88b3-48ee5e304e02">


# 20 LABS

CREATING AN ERC20 TOKEN INVOLVES A SOLIDITY CONTRACT THAT IMPLEMENTS THE ERC20 TOKEN STANDARD.
THIS CONTRACT WILL DEFINE THE TOKEN'S PROPERTIES, SUCH AS THE TOTAL SUPPLY, SYMBOL, NAME,
DECIMALS, AND TOKEN BALANCES FOR EACH ADDRESS.

1. GO TO GIVEN LINK: https://20lab.app/ (20LAB IS AN ERC-20 TOKEN GENERATOR TOOL).
2. CLICK ON OPEN APP > START.
3. CONNECT YOUR WALLET USING CONNECT WALLET BUTTON AND SELECT METAMASK THEN ONCE YOU SEE YOUR ACCOUNT CLICK ON CONNECT.
4. CHOOSE BLOCKCHAIN GORELI(TESTNET), THEN ENTER YOUR TOKEN NAME, TOKEN SYMBOL, INITIAL SUPPLY (TAKE VERY LARGE NUMBER), 18 DECIMALS.
5. SELECT YOUR DESIRED OPTIONS AND CLICK VALIDATE & COMPILE, IT WILL OPEN METAMASK AND ASK FOR GAS FEE FOR
6. DEPLOYING YOUR TOKEN.
7. VIEW YOUR TOKEN NAME AND ADDRESS IN DASHBOARD (I NAMED MY TOKEN AS AYUSH AND KEPT ITS SYMBOL AR).



<img width="1440" alt="Screenshot 2023-06-29 at 4 36 08 PM" src="https://github.com/AYUSH363/BLOCKCHAIN/assets/120236457/d3d9ac6b-a7ea-44b5-b0f3-a2ada92d9c94">


# ETHERSCAN

TO CHECK THE TRANSACTION HISTORY OF THE TOKEN GO TO https://goerli.etherscan.io/ AND PASTE YOUR TOKEN ADDRESS FROM 20LAB.





<img width="1440" alt="Screenshot 2023-06-29 at 4 32 43 PM" src="https://github.com/AYUSH363/BLOCKCHAIN/assets/120236457/03be801d-ae08-41a9-a545-373481851256">

# HYPERLEDGER-FABRIC

TO INITIATE THE FIRST HYPERLEDGER FABRIC NETWORK, WE WILL UTILIZE THE FABRIC-SAMPLES REPOSITORY. THIS REPOSITORY CONSISTS OF CLI TOOL BINARIES AND FABRIC DOCKER IMAGES, WHICH ARE ESSENTIAL FOR COMPREHENDING AND UTILIZING THE FUNDAMENTALS OF FABRIC. BEFORE COMMENCING THE PROJECT, IT IS NECESSARY TO INSTALL THE FOLLOWING DEPENDENCIES

# 1. INSTALL DOCKER
    sudo apt install golang-go

# 2. INSTALL GOLANG-GO
    sudo apt install golang-go

# 3. INSTALL JQ
    sudo apt install jq

# 4. INSTALL NODE/JAVA
    sudo apt install npm
    npm install node

# 5. INSTALLING FABRIC-SAMPLES REPOSITORY

    curl -sSLO https://raw.githubusercontent.com/hyperledger/fabric/main/scripts/install-fabric.sh && chmod +x install-fabric.sh

THEN YOU CAN PULL DOCKER CONTAINERS BY RUNNING ONE OF THESE COMMANDS:

    ./install-fabric.sh docker samples
    ./install-fabric.sh d s

TO INSTALL BINARIES FOR FABRIC SAMPLES YOU CAN USE THE COMMAND BELOW:

           ./install-fabric.sh binary


# BUILDING FIRST NETWORK

1. NAVIGATE THROUGH THE FABRIC-SAMPLES FOLDER AND THEN THROUGH THE TEST NETWORK FOLDER WHERE YOU CAN FIND SCRIPT FILES USING THESE WE CAN RUN OUR NETWORK

       cd fabric-samples/test-network
2. WE WOULD BE RUNNING ./NETWORK.SH DOWN COMMAND TO REMOVE ANY PREVIOUS NETWORK CONTAINERS OR ARTIFACTS THAT STILL EXIST


       ./network.sh down

3. WE CAN BRING UP A NETWORK USING THE FOLLOWING COMMAND. THIS COMMAND CREATES A FABRIC NETWORK THAT CONSISTS OF TWO PEER NODES AND ONE ORDERING NODE

       ./network.sh up


NOW OUR FIRST HYPERLEDGER FABRIC NETWORK IS SUCCESSFULLY RUNNING.


