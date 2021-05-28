#Yarn.Money is Cross-chain EVM-based Tokens to earn more yield from various chain

* Ethereum 
* Binance Smart Chain
* Reduce the transaction fees with Polygon Bridge and xDAI bridge
* All fees 100% rebate to holder

Live data source available when the project launch

If you interested to invest on the project. kindly email fund@yarn.money(./deploy.md)

💠Github (https://github.com/cryptobizchannel/yarn.money)
💠 Join the YarnMoney Telegram group (http://t.me/yarnmoney) 
💠 Follow YarnMoney Twitter (https://twitter.com/yarnmoney) 
💠 Follow YarnMoney Medium (http://www.medium.com/@yarnmoney 
💠 Follow YarnMoney Instagram (https://www.instagram.com/yarnmoney

## Example

```json
"yfi": {
  "srcChainID": "1",
  "destChainID": "56",
  "PairID": "YFI",
  "SrcToken": {
    "ID": "YMY",
    "Name": "yarn.money",
    "Symbol": "YMY",
    "Decimals": 18,
    "Description": "yarn.money",
    "DepositAddress": "0x402C27341d13b0c23a01cF39794f875eF0887B16",
    "mpcAddress": "0x13B432914A996b0A48695dF9B2d701edA45FF264",
    "ContractAddress": "0x912f4646c554dbddea285e81f92dcac635893900",
    "MaximumSwap": 20,
    "MinimumSwap": 0.0005,
    "BigValueThreshold": 5,
    "SwapFeeRate": 0,
    "MaximumSwapFee": 0,
    "MinimumSwapFee": 0,
    "PlusGasPricePercentage": 10,
    "DisableSwap": false,
    "IsDelegateContract": false
  },
  "DestToken": {
    "ID": "anyYMY",
    "Name": "YMY-ERC20",
    "Symbol": "anyYMY",
    "Decimals": 18,
    "Description": "cross chain bridge YMY with anyYMY",
    "mpcAddress": "0x13B432914A996b0A48695dF9B2d701edA45FF264",
    "ContractAddress": "0x912f4646c554dbddea285e81f92dcac635893900",
    "MaximumSwap": 20,
    "MinimumSwap": 0.002,
    "BigValueThreshold": 2,
    "SwapFeeRate": 0.001,
    "MaximumSwapFee": 0.01,
    "MinimumSwapFee": 0.001,
    "PlusGasPricePercentage": 1,
    "DisableSwap": false,
    "IsDelegateContract": false
  }
}
```

# EVM-based Chains

 * [chainlist.org](https://chainlist.org)
 * [chainid.network](https://chainid.network)

Listed by chainId according to EIP-155

Data source available on [~/ethereum-lists/chains/_data/chains.json](https://github.com/ethereum-lists/chains/tree/master/_data/chains)

## Example

```json
{
  "name": "Ethereum Mainnet",
  "chain": "ETH",
  "network": "mainnet",
  "rpc": [
    "https://mainnet.infura.io/v3/${INFURA_API_KEY}",
    "https://api.mycryptoapi.com/eth"
  ],
  "faucets": [],
  "nativeCurrency": {
    "name": "Ether",
    "symbol": "ETH",
    "decimals": 18
  },
  "infoURL": "https://ethereum.org",
  "shortName": "eth",
  "chainId": 1,
  "networkId": 1
}
