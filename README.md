# Is_PupperCoin_Obiting
## _Crowd-selling PupperCoin to Discover Interesting Facts on our best friends_

## **Overview**
Crowd-selling PupperCoin coded on Solidity to fund generic trailing project on pups. Two contracts are written and deployed on Remix. 

* The _ENVIRONMENT_ on Remix is set to _**INJECTED WEB3**_ 

* MetaMask is tuned in _**KOVAN Test Network**_.


---

## _**[CrowdSale](Code/Crowdsale.sol)**_

### **Transaction on EtherScan for Puppercoin Contract Deployment**
![Transaction of puppercoin](Images/tx_etherscan_puppercoin.png)

### **Crowdsale Contract Deployment on Remix**

**Step 1. Deploy PupperCoinsSale Deployer Contract**

i) Enter the following information at **DEPLOY**:
```
NAME: PupperCoin
SYMBOL: PUP
WALLET: 0x5DBaBe19DD1fedba1B20047059DCd755D8221BF7
GOAL: 10000
```
ii) Click on **transact** button. 

![PupperCoinSaleDeployer Deployment](Images/pup_deploy_kovan_001.png)

iii) Confirm on MetaMask pop-up window.

**Step 2. Deploy PupperCoinsSale Contract**

i) View addresses by clicking on blue buttons 
* pupper_token_address
* token_address

ii) Scroll CONTRACT to PupperCoinSale
<details><summary>
at pupper_token_address circled below:
</summary>

![PupperCoinSale Deployment](Images/pup_deploy_kovan_002.png)

</details>

**Step 3. Deploy PupperCoins Contract**

---
## _**[PupperCoin](Code/PupperCoin.sol)**_

### **Transaction on EtherScan for Puppercoin buyTokens**
![Transaction of puppercoin](Images/pup_tx_kovan_etherscan_001.png)

### **Puppercoin Contract Deployment on Remix**
<details><summary>
at token_address 
</summary>

![PupperCoin Remix Deployment 2](Images/pup_deploy_kovan_003.png)

</details>

---

## _**Features**_


### **A. Buy Tokens under PupperCoinSale on Remix**

![PupperCoin buyTokens](Images/pup_buytokens_kovan_004.png)

_**Looks like it is a sucess!**_

![PupperCoin buyTokens](Images/pup_tx_kovan_etherscan_002.png)


<details><summary>
Here is another buyTokens transaction for 3000 wei PupperCoin
</summary>

![PupperCoin buyTokens 3000](Images/pup_buytokens_kovan_tx3000.png)

</details>

### **B. Approve Spending PUP**

<details><summary>
Click on `approve` under PUPPERCOIN contract
</summary>

![PupperCoin Approve](Images/pup_approve_kovan.png)

</details>


### **C. Check Balance**

<details><summary>
Check balance by clicking on `balanceOf` under deployed `PupperCoinSale` Contract
</summary>

![PupperCoin buyTokens 3000](Images/pup_tx_kovan_etherscan_003.png)

</details>

### **D. Add Tokens**

<details><summary>
Add Tokens by entering wallet Address, symbol `PUP` and 18 for decimals
</summary>

![PupperCoin Add Tokens](Images/pup_kovan_token_0.png)

![PupperCoin with PUP Tokens](Images/pup_kovan_token.png)


</details>

### **E. Transfer Tokens**

<details><summary>
Click on `transfer` under `PUPPERCOIN` function
</summary>

![PupperCoin buyTokens 3000](Images/pup_tx_kovan_003.png)

</details>

---

## **View Tokens on MyCrypto Wallet**

<details><summary>
Access wallet on MyCrypto via the PRIVATE KEY in Ganache.
</summary>

![Ganache](Images/ganache_address.png)

</details>

Press _**Scan for Tokens**_ button on the bottom right corner:

![PupperCoin buyTokens 3000](Images/pup_mycrypto_rinkeby_1.png)

---
## The above processes can be done on Rinkeby and Ropsten Testnets by adjusting the network on MetaMask.

### _**On Rinkeby**_

![Rinkeby Etherscan Transaction](Images/rinkeby_etherscan_1.png)


---
_**More Love for Pups**_

For getting testcoins, both Kovan and Ropsten faucets could do the job!

<details><summary>
Kovan Testcoins
</summary>

![Kovan Faucet](Images/faucet_kovan.png)

</details>

<details><summary>
Ropsten Testcoins
</summary>

![Ropsten Faucet](Images/faucet_ropsten.png)

</details>

<details><summary>
Tweet for Rinkeby Testcoins
</summary>

_**Step 1: Go to [Rinkeby Faucet](https://faucet.rinkeby.io/)**_

![Rinkeby Authorization 1](Images/rinkeby_auth_1.png)

_**Step 2: Tweet the message with designated wallet address**_

![Rinkeby Authorization 2](Images/rinkeby_auth_2.png)

_**Step 3: Copy link on posted message on Twitter**_

![Rinkeby Authorization 3](Images/rinkeby_auth_3.png)

_**Step 4: Verify tweet**_

![Rinkeby Authorization 4](Images/rinkeby_auth_4.png)

_**Step 5: Check balance on MetaMask**_

![Rinkeby Authorization 5](Images/rinkeby_auth_5.png)


</details>

---
## Files

**[PupperCoin](Code/PupperCoin.sol)**

**[CrowdSale](Code/Crowdsale.sol)**

**[Kovan Transactions](Transactions/Kovan)**

**[Rinkeby Transactions](Transactions/Rinkeby)**

**[Images Folder](Images)**

---

# References
* Columbia University Fintech Bootcamp Repository
* http://remix.ethereum.org/
* https://faucet.ropsten.be/
* https://kovan.etherscan.io/
* https://solidity.readthedocs.io/
* https://medium.com/coinmonks/create-token-contract-and-time-limited-crowdsale-contract-with-whitelisting-in-solidity-1eb979d206f6
* https://ethereum.stackexchange.com/questions/51757/basic-crowdsale-contract
* https://ethereum.stackexchange.com/questions/51757/basic-crowdsale-contract
* https://github.com/raineorshine/solidity-by-example
* https://github.com/bkrem/awesome-solidity
* https://solidity.readthedocs.io/en/v0.5.3/solidity-by-example.html#simple-open-auction