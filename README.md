The simpleStorage.sol has been compiled by solcjs with the command yarn solcjs --bin --abi --include-path node_modules/ --base-path . -o . SimpleStorage.sol
or yarn compile to run that cmd.
Then with the deploy script we deployed in the local Ganache by $node deploy.js
Most of the project we use .env to specify our priv keys and addr, or RPC url's but in the professional set we want our priv keys and data to be even more secure. so we can encrypt(encryptKey.js) our priv key and store the encrypted key locally.
