# test-atomic-swaps
Output of this code:- 
Output:-


PS C:\Users\ok\Downloads\testing-atomic-swaps> truffle migrate --reset --network sepolia


Compiling your contracts...
===========================
> Compiling @openzeppelin\contracts\token\ERC20\ERC20.sol
> Compiling @openzeppelin\contracts\token\ERC20\IERC20.sol
> Compiling @openzeppelin\contracts\token\ERC20\extensions\IERC20Metadata.sol
> Compiling @openzeppelin\contracts\utils\Context.sol
> Compiling .\contracts\HTLC.sol
> Compiling .\contracts\Migrations.sol
> Compiling .\contracts\Token.sol
> Artifacts written to C:\Users\ok\Downloads\testing-atomic-swaps\build\contracts
> Compiled successfully using:
   - solc: 0.8.0+commit.c7dfd78e.Emscripten.clang




Migrations dry-run (simulation)
===============================
> Network name:    'sepolia-fork'
> Network id:      11155111
> Block gas limit: 30000000 (0x1c9c380)




1_initial_migration.js
======================


   Replacing 'Migrations'
   ----------------------
   > block number:        4672925
   > block timestamp:     1699712642
   > account:             0x1AdEbb80cEC422926C24F6a2CDFD755961b01959
   > balance:             0.455550360646914531
   > gas used:            245656 (0x3bf98)
   > gas price:           2.500000009 gwei
   > value sent:          0 ETH
   > total cost:          0.000614140002210904 ETH


   -------------------------------------
   > Total cost:     0.000614140002210904 ETH




2_deploy_contracts.js
=====================
   -------------------------------------
   > Total cost:                   0 ETH


Summary
=======
> Total deployments:   1
> Final cost:          0.000614140002210904 ETH








Starting migrations...
======================
> Network name:    'sepolia'
> Network id:      11155111
> Block gas limit: 30000000 (0x1c9c380)




1_initial_migration.js
======================


   Replacing 'Migrations'
   ----------------------
   > transaction hash:    0xb481f6f3e2197180f6cae3d7a06065b45f32768b23428e1a4f7899ca719625d2
   > Blocks: 2            Seconds: 17
   > contract address:    0x36FeC1fB60e8b8cC5D465a981Cd6BF63A07aeA2e
   > block number:        4672931
   > block timestamp:     1699712688
   > account:             0x1AdEbb80cEC422926C24F6a2CDFD755961b01959
   > balance:             0.455550360646914531
   > gas used:            245656 (0x3bf98)
   > gas price:           2.500000009 gwei
   > value sent:          0 ETH
   > total cost:          0.000614140002210904 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:     0.000614140002210904 ETH




2_deploy_contracts.js
=====================


   Replacing 'Token'
   -----------------
   > transaction hash:    0xb3c0b998054800098c7111a119dcb8b48c1480fa2ad31618a049033df0fc7d9d
   > Blocks: 2            Seconds: 17
   > contract address:    0x849914f6B76373f737e736b7FAE150846704D9f6
   > block number:        4672934
   > block timestamp:     1699712724
   > account:             0x1AdEbb80cEC422926C24F6a2CDFD755961b01959
   > balance:             0.452543433136089592
   > gas used:            1156858 (0x11a6fa)
   > gas price:           2.500000009 gwei
   > value sent:          0 ETH
   > total cost:          0.002892145010411722 ETH




   Replacing 'HTLC'
   ----------------
   > transaction hash:    0x623fe4bde959a0cbaae91ca326ea2bd12c1a82d8022697aefd9f5e137940853b
   > Blocks: 2            Seconds: 17
   > contract address:    0x421D245df7015e99e447aDDE93a12AE5bca698F4
   > block number:        4672936
   > block timestamp:     1699712748
   > account:             0x1AdEbb80cEC422926C24F6a2CDFD755961b01959
   > balance:             0.450290483127978972
   > gas used:            901180 (0xdc03c)
   > gas price:           2.500000009 gwei
   > value sent:          0 ETH
   > total cost:          0.00225295000811062 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:     0.005145095018522342 ETH


Summary
=======
> Total deployments:   3
> Final cost:          0.005759235020733246 ETH




PS C:\Users\ok\Downloads\testing-atomic-swaps> truffle migrate --reset --network binanceTestnet


Compiling your contracts...
===========================
> Compiling @openzeppelin\contracts\token\ERC20\ERC20.sol
> Compiling @openzeppelin\contracts\token\ERC20\IERC20.sol
> Compiling @openzeppelin\contracts\token\ERC20\extensions\IERC20Metadata.sol
> Compiling @openzeppelin\contracts\utils\Context.sol
> Compiling .\contracts\HTLC.sol
> Compiling .\contracts\Migrations.sol
> Compiling .\contracts\Token.sol
> Artifacts written to C:\Users\ok\Downloads\testing-atomic-swaps\build\contracts
> Compiled successfully using:
   - solc: 0.8.0+commit.c7dfd78e.Emscripten.clang




Starting migrations...
======================
> Network name:    'binanceTestnet'
> Network id:      97
> Block gas limit: 50000000 (0x2faf080)




1_initial_migration.js
======================


   Replacing 'Migrations'
   ----------------------
   > transaction hash:    0x55a36182198fdcecc3db7d2fea4a492de3508f8165ced339943ba3599d9737eb
   > Blocks: 2            Seconds: 5
   > contract address:    0x2A203339A90a837B5f00483291Ae69caC284e516
   > block number:        35005002
   > block timestamp:     1699712806
   > account:             0x1AdEbb80cEC422926C24F6a2CDFD755961b01959
   > balance:             0.1980432175
   > gas used:            245600 (0x3bf60)
   > gas price:           2.5 gwei
   > value sent:          0 ETH
   > total cost:          0.000614 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:            0.000614 ETH




2_deploy_contracts.js
=====================


   Deploying 'Token'
   -----------------
   > transaction hash:    0x76ab924b7073201f0110006065d752db75e31f34cfeaf7e62d8913cb3de8a2f8
   > Blocks: 7            Seconds: 20
   > contract address:    0xb7061Dac82E09852Dff2025279BDAaC31cfCfD96
   > block number:        35005018
   > block timestamp:     1699712854
   > account:             0xBa58166D1692C74c3d7e88f8Bf0bAAd378E177A4
   > balance:             0.191965405
   > gas used:            1156460 (0x11a56c)
   > gas price:           2.5 gwei
   > value sent:          0 ETH
   > total cost:          0.00289115 ETH




   Deploying 'HTLC'
   ----------------
   > transaction hash:    0x66e2bf4713cf0a66d5fcd82ca7e5cd9a1ac9bb0bbf4c341c4c469e263d6b18d7
   > Blocks: 5            Seconds: 16
   > contract address:    0x56df581d68C36b85c463d6958B249B540a4052AB
   > block number:        35005026
   > block timestamp:     1699712878
   > account:             0xBa58166D1692C74c3d7e88f8Bf0bAAd378E177A4
   > balance:             0.18971308
   > gas used:            900930 (0xdbf42)
   > gas price:           2.5 gwei
   > value sent:          0 ETH
   > total cost:          0.002252325 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:         0.005143475 ETH


Summary
=======
> Total deployments:   3
> Final cost:          0.005757475 ETH



Terminal Commands to be used:-
=======

> Truffle migrate –reset –network sepolia <br/>
> Truffle migrate –reset –network binanceTestnet

<h6>
For Bob withdrawing token
Truffle console –network binanceTestnet <br/>
Const addresses = await web3.eth.getAccounts() <br/>
a) gets both addresses
Const htlc = await HTLC.deployed() <br/>
htlc.address <br/>
Await htlc.withdraw(secret,, {from:address[0]}) <br/>
Const token = await Token.deployed() <br//>
Const balance = await token.balanceOf(addresses[0]) <br/>
balance.toString() <br/>

Output will look like this below:-

PS C:\Users\ok\Downloads\testing-atomic-swaps> truffle console --network binanceTestnet      <br/>   
truffle(binanceTestnet)> const addresses = await web3.eth.
getAccounts() <br/>
undefined<br/>
truffle(binanceTestnet)> addresses 
[
  '0x1AdEbb80cEC422926C24F6a2CDFD755961b01959',
  '0xBa58166D1692C74c3d7e88f8Bf0bAAd378E177A4'
]
truffle(binanceTestnet)> const htlc = await HTLC.deployed(
)
undefined
truffle(binanceTestnet)> htlc.address
'0x56df581d68C36b85c463d6958B249B540a4052AB'
truffle(binanceTestnet)> await htlc.withdraw('abracadabra'
,{from:addresses[0]})
{
  tx: '0x5b7aeffdb673103efbb991272c3c4f7b9bf1ac0e1a8c007fcddd3d35cba3b439',
  receipt: {
    blockHash: '0xab15796bfd6b5e842f4b0ec07bfa54e662b91b1d0033d572b16bfe5110214e25',
    blockNumber: 35005170,
    contractAddress: null,
    cumulativeGasUsed: 511807,
    effectiveGasPrice: 2500000000,
    from: '0x1adebb80cec422926c24f6a2cdfd755961b01959',   
    gasUsed: 83177,
    logs: [],
    logsBloom: '0x00020000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000000000000004008000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000010000000000000000000000000000010000000000000000000000010000080000000000000000000000000008000000000000000000000000000000000000000000000000000000002000000000000000000000000000000000000000000000000000000002000000000000000000000000000000000000000000000000000000000000000',
    status: true,
    to: '0x56df581d68c36b85c463d6958b249b540a4052ab',     
    transactionHash: '0x5b7aeffdb673103efbb991272c3c4f7b9bf1ac0e1a8c007fcddd3d35cba3b439',
    transactionIndex: 4,
    type: '0x2',
    rawLogs: [ [Object] ]
  },
  logs: []
}
truffle(binanceTestnet)> const token = await Token.deploye
d()
undefined <br/>
truffle(binanceTestnet)> const balance = await token.balan
ceOf(addresses[0]} <br/>
evalmachine.<anonymous>:1
          await token.balanceOf(addresses[0]}
                                           ^

Uncaught SyntaxError: missing ) after argument list       
truffle(binanceTestnet)> const balance = await token.balanceOf(addresses[0])}
evalmachine.<anonymous>:1
          await token.balanceOf(addresses[0])}
                                             ^

Uncaught SyntaxError: Unexpected token '}'
truffle(binanceTestnet)> const balance = await token.balanceOf(addresses[0])
undefined
truffle(binanceTestnet)> balance.toString()
'1'

Here you can see above balance.toString returns 1 which is that the token has been transferred similarly the same thing can be done for the other side as well.

Come outside the console, open another terminal

For Alice withdrawing token
Truffle console –network sepolia
i) const addresses = await web3.eth.getAccounts()
ii) const htlc = await HTLC.deployed()
iii) htlc.addresses

In binance test do
Const mySecret = await htlc.secret()
Copy the secret
	iv) Copy the secret above and write await htlc.withdraw(secret,{from:addresses[1]})
	v) const token = await Token.deployed()
	vi) const balance = await token.balanceOf(addresses[1])
	vii) balance.toString()

Output:-
PS C:\Users\ok\Downloads\testing-atomic-swaps> truffle console --network sepolia <br/>
truffle(sepolia)> const addresses = await web3.eth.getAccounts() <br/>
undefined <br/>
truffle(sepolia)> const htlc = await HTLC.
deployed() <br/>
undefined <br/>
truffle(sepolia)> htlc.address
'0x421D245df7015e99e447aDDE93a12AE5bca698F4' <br/>

truffle(sepolia)> await htlc.withdraw('abracadabra',{from:addresses[1]})
  tx: '0x8a239a39cd72ca0a435aca9a7781d5655f09196366fb067e10fd72c061e47e1b',
  receipt: {
    blockHash: '0xb487938c6d6bbe2122035ed8e72fb585126c7ff37787d2da4c5b71a018daf68b',
    blockNumber: 4673035,
    contractAddress: null,
    cumulativeGasUsed: 1236575,
    effectiveGasPrice: 2500000010,        
    from: '0xba58166d1692c74c3d7e88f8bf0baad378e177a4',
    gasUsed: 42876,
    logs: [],
    logsBloom: '0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000',
    status: false,
    to: '0x421d245df7015e99e447adde93a12ae5bca698f4',
    transactionHash: '0x8a239a39cd72ca0a435aca9a7781d5655f09196366fb067e10fd72c061e47e1b',
    transactionIndex: 3,
    type: '0x2',
    rawLogs: []
  },
  reason: undefined,
  hijackedStack: ''
}
truffle(sepolia)> const token = await Token.deployed()
undefined
truffle(sepolia)> const balance = await token.balanceOf(addresses[1])
undefined
<br/>
truffle(sepolia)> balance.toString() <br/>
'1'
</h6>
