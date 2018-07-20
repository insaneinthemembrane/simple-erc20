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

11. Press "confirm" and your metamask wallet will open, asking you to submit. You can alter the gwei and gas if you want to

12. Press "submit" and that is that. Your contract will now be confirming. It can take between 30 seconds and 10 minutes. The more gas and higher gwei you paid, the faster it should be. If you did not pay enough, or used insufficient gas, the transaction will fail

13. Give it 2 minutes, then search your metamask address on etherscan, and you should find the transaction, hopefully confirmed

14. Now you need to confirm the source code. After finding the completed transaction, click "confirm source". Then paste a copy of the source code you used into the box. Next, select the compiler version you used (0.4.19). Next either click that "optimazation" was enabled, or click that it was not. Then submit. If everything is correct, the source will be verified.

15. You should be able to click on the links, or paste your address into search to find all details of the verified source code. It sometimes takes a few minutes before it is completely visible.


# Adding tokens to your wallet

You used metamask, but metamask is shit for sending tokens. Use [myetherwallet](https://myetherwallet.com) instead. Firstly, open your metamask wallet and copy the 16 word phrase. Use that to open your wallet at myetherwallet.

Then add the token.

See the explanation here: myetherwallet](https://github.com/insaneinthemembrane/ERC20-Adding-Token) 
