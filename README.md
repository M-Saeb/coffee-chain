# Coffee Chain
A Dapp for tracking coffee's supply Chain life cycle, from harvesting the the beens by the formed. To purchasing them by the consumer.


## Description
- The [Activity Diagram](Diagrams%20%26%20images/Activity%20Diagram.png) shows the complete life cycle for the dapp
- The [Class Diagram](Diagrams%20%26%20images/Class%20Diagram.png) shows the complete code structor for the [coffeeaccesscontrol](contracts/coffeeaccesscontrol/) contracts 
- The [Sequence Diagram](Diagrams%20%26%20images/Sequence%20Diagram.png) shows the sequence for the functions in the [SupplyChain](contracts/coffeebase/SupplyChain.sol) contract
- The [State Diagram](Diagrams%20&%20images/State%20Diagram.png) shows the state for items in the supplychain & how they reflect in the [SupplyChain](contracts/coffeebase/SupplyChain.sol) contract
- The [Event Hash](Diagrams%20%26%20images/Events%20Hash.png) shows the hash for each transaction ran for the contract on the rinkeby network



## Requiments
```
Truffle version: v4.1.14 (core: 4.1.14)
Solidity version: v0.4.24 (solc-js)
node version: v10.16.3
web3 version: ^1.2.6
```

## Deployments
- The main cotract is deployed on the rinkeby network under the following address:
https://rinkeby.etherscan.io/address/0x5c211838de48fffeca8f0ec9aa3405c3452f2e6b
- [this](Diagrams%20%26%20images/Events%20Hash.png) shows each event done on the rinkeby contract