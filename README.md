
<div align="center">
  <h1>vKYC Chain for a Banking Consortium</h1>
</div>
<br>

<br/>

**Demo Website** : [https://vkyc.netlify.app/](https://vkyc.netlify.app/)<br/>

<!-- ABOUT THE PROJECT -->

<!-- Key Features -->
## **Key Features**
<br>
<ul>
  <li>Client and Bank Registration</li>
  <li>Crypto Wallet-less UI for Clients</li>
  <li>Additional Layer of Authorisation Protecting Client Data</li>
  <li>Admin Panel</li>
  <li>Decentralized IPFS for Documents</li>
  <li>Detailed User Dashboard</li>
  <li>Entire Customer KYC History Visualisation</li>
  <li>Geo-tagging</li>
  <li>In-built Video KYC Platform</li>
</ul>  
<br>
<br>

### **Tech Stack used**

* [Ethereum Smart Contracts](https://ethereum.org/en/developers/docs/smart-contracts/)
* [InterPlanetary File System (IPFS)](https://ipfs.io/)
* [Solidity](https://docs.soliditylang.org/en/v0.8.11/)
* [React.js](https://reactjs.org/)
* [Node.js](https://nodejs.org/)
* [Web3.js](https://web3js.readthedocs.io/en/v1.5.2/getting-started.html)
* [MongoDb](https://www.mongodb.com/)
* [Ganache GUI](https://trufflesuite.com/ganache/)
* [MetaMask](https://metamask.io/)


<br/>

## Step 1. Clone the project
`git clone <github link>`

## Step 2. Install dependencies
```
$ cd Blockchain based Digital Identity & video-KYC
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. You can also use other local blockchains.

## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the verification smart contract each time your restart ganache.

## Step 5. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm start`
Visit this URL in your browser: http://localhost:3000

## Step 6. Run the Back End Application
`$ npm run server`
Visit this URL in your browser: http://localhost:5000

