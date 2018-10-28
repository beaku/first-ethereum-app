# first-ethereum-app
This app is deployed on the Rinkeby Test Network and contains one test variable which can be updated by a method.
Puppeth is a tool to aid you in creating a new Ethereum network down to the genesis block, bootnodes, signers, ethstats server, crypto faucet, wallet browsers, block explorer, dashboard and more; without the hassle that it would normally entail to manually configure all these services one by one.

Puppeth uses ssh to dial in to remote servers, and builds its network components out of docker containers using docker-compose. The user is guided through the process via a command line wizard that does the heavy lifting and topology configuration automatically behind the scenes.


Puppeth is distributed as part of the Geth & Tools bundles, but can also be installed separately via:

go get github.com/ethereum/go-ethereum/cmd/puppeth
