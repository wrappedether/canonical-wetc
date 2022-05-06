# Canonical W-ETC

## Canonical [W-ETC](https://wrappedether.org/) package.

Inspiration from Canonical [W-ETH](https://weth.io/) package. See: https://blog.0xproject.com/canonical-weth-a9aa7d0279dd)

## Usage

```sh
npm install --save truffle-contract canonical-weth
```

and

```js
const contract = require('truffle-contract');
const wethArtifact = require('canonical-weth');

const weth = contract(wethArtifact);
```

## Deployed contract addresses

- Mainnet: [0x1953cab0E5bFa6D4a9BaD6E05fD46C1CC6527a5a](https://blockscout.com/etc/mainnet/address/0x1953cab0E5bFa6D4a9BaD6E05fD46C1CC6527a5a)
- Kotti: [0x1953cab0E5bFa6D4a9BaD6E05fD46C1CC6527a5a](https://blockscout.com/etc/kotti/address/0x1953cab0E5bFa6D4a9BaD6E05fD46C1CC6527a5a)
- Mordor: [0x1953cab0E5bFa6D4a9BaD6E05fD46C1CC6527a5a](https://blockscout.com/etc/mordor/address/0x1953cab0E5bFa6D4a9BaD6E05fD46C1CC6527a5a/transactions)
