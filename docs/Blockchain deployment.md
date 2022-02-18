### Blockchain deployment


1. You can check all our differents smart contracts in contract folder:

![alt text](/img/contracts.png)


2. To Deploy smart contracts (token,campaign and oracle) in contract folder with [Remix](https://remix.ethereum.org) and [Metamask](https://metamask.io/) or [MEW](https://www.myetherwallet.com/):

**create your file on Remix and paste your code there

![alt text](/img/remix.png)

**Compile your file.sol and check


![alt text](/img/compile.png)


**To deploy your smart contract you should connect with your metamask account 

![alt text](/img/deploy.png)

3. To create node, Web3 service provider with [Geth](https://geth.ethereum.org/),[openethereum](https://github.com/openethereum/openethereum) or [Infura](https://infura.io/) SaaS

**Create new Ethereum app


![alt text](/img/createinfura.png)


**Get node credentials from infura such as PROJECTID, PROJECT SECRET, and the endpoints that we can use to connect to infura node(https, wss)


![alt text](/img/keysinfura.png)


```sh
WEB3_URL=process.env.WEB3_URL
```



You can also install Geth Node you can follow this [Guide](https://geth.ethereum.org/docs/getting-started) or [Parity](https://openethereum.github.io/Setup)

4. on campaign contract call modToken(<token_address>,true)
5. on campaign contract call setOracle(<oracle_address>)
6. on oracle contract call changeAsk(<campaign_address>,true)
