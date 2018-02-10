# WednesdayCoinTransfer
Transfer page for WednesdayCoin

The entire page is essentialy in Beta. This is a simple little webpage that I wrote up to make it easy to transfer and interact with WednesdayCoin through a web page. This page uses web3js to directly interface with the contract. This allows the page to execute any function from the contract. I am using this for airdrops as I modified it to support transferring to multiple addresses.

# Requirements
1. node - to check run: node -v 
2. npm - to check run: npm -v
3. web3js
4. Ethereum address validator
5. Python - for running a server locally

# Install/Usage
1. Run the node and npm commands above to ensure that your system has both. If not you will need to install both. 
2. Check out the html file, since that is really all that is necessary. 
3. Using a terminal or command prompt cd to directory with html
4. run: npm init
5. run: npm install ethereum/web3.js --save
6. run: npm install ethereum-address
7. Once those are done you should have a node-modules folder with the necessary modules
8. run: python -m SimpleHTTPServer 8000
9. In a browser with ether metamask or in mist browser go to http://localhost:8000 to access the page

# Fun Stuff
I wrote this for WednesdayCoin so the contract address is hardcoded on the page. This can be expanded to be a dropdown like myetherwallet or this can be forked and written as a custom transfer page for any ERC20 token. To do this all that really needs to be updated is the contract address and ABI (Application Binary Interface) which can be gotten from loading the contract into remix online editor and clicking the detials section next to compile and scrolling down to the interface - ABI section.

