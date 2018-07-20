# simple-erc20

-----

# Requirements

- Completed source code
- Metamask app for Google Chrome (and Google Chrome)
- Some ETH in the Metamask wallet

-----

# Steps

1. Copy paste the [source code](https://github.com/insaneinthemembrane/simple-erc20/blob/master/YOURTOKEN.sol) onto a text document. Change the paramaters with comments (and then remove comments).

2. Go to the [online solidity compiler](http://remix.ethereum.org) and paste the new source code into it. It shoud begin compiling.

3. Click "settings", top-right of the screen. In the drop-down menu ("select compiler version") select a compiler. Do NOT use a "nightly" version. Use a simple "commit". I use 0.4.19.

4. Underneath are "general settings". Either select "enable optimization" or deselect it. Just remember whether it was selected or not for when you confirm the source code.

5. Go back to "compile" in the menu

6. The source code should have compiled by itself. Do not worry about the "warnings". 

7. Click on your metamask wallet in your browser menu, and enter the password to open it

8. Click on "run", top-right menu. You want the contract to be called after your token (see box). If it is not, click the box and select the "token name".

9. To make sure you get the tokens, put your metamask eth address in the box, "load contract from this address". Click "at address", and your metamask eth address should load ("deployed contracts")

10. Now, deploy the contract, simply by clicking "deploy" If nothing happens, refresh the page, and click on "run" in the menu, your contract should load. Click "deploy" again, and a massive blue box pops up with details of the transaction. Go to the bottom and accept (you may want to make the gas price higher first, or not)
