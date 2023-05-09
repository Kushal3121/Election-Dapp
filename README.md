#Election-Dapp - 

## Setup
### Dependencies
<ul>
  <li>NPM: https://nodejs.org</li>
  <li>Truffle: https://github.com/trufflesuite/truffle</li>
  <li>Ganache: http://truffleframework.com/ganache/</li>
  <li>Metamask: https://metamask.io/</li>
</ul>  

### Step 1. Clone the project
`git clone https://github.com/Kushal3121/Election-Dapp.git`

### Step 2. Install dependencies
```
$ cd election-dapp
$ npm install
```
### Step 3. Start Ganache
Open the Ganache GUI client. This will start your local blockchain instance.


### Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

### Step 5. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

### Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000
