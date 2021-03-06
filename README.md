# About famacoinWallet

famacoinWallet (fW) is a minimal browser application wholly devoted to Famacoin (fmc) transactions. fW does not allow explicit Ether (eth) transactions, yet. It is in progress now ...

You can run famacoinWallet from  <a href="https://famacoin.org/famacoinwallet/">famacoin.org</a> or you can download all scripts, unzip them and run this browser application from the ~/famacoinWallet-master/index.html local folder. Before running this downloaded wallet, you must edit the index.html file and place your <a href="https://infura.io/">own infura key </a>where it says '"put_your_infura_code_here', into web3 infura provider row.

fW is using the basic infura web3 provider, and web3.min.js, jquery-3.4.1.min.js, ethereumjs-tx-1.3.3.min.js and famacoin.min.js modules, to make interactions with Famacoin smart contract on the Ethereum blockchain. In addition, it is using the qrcode.min.js module to generate the QR code of the public address.

# About Use

famacoinWallet cannot be used to perform offline fmc transactions or any other offline active interaction with the Famacoin smart contract.

fW only does four basic things:

1. Check balances of fmc and eth. Balances appear automatically when an Ethereum public address is added using the "choose address with public key" option or "choose address with private key" option.
2. Transfer fmc from a wallet to another using the "fmc transfer..." option.
3. Close and open an auction using the "close auction..." option.
4. Make a bid using the "make a bid..." option.

The last three options require using the private key, so you must proceed with care.

# About Security

Please note that fW is in progress now so you must not use real Ether account yet. fW has not been through a comprehensive security review at this point. It is still experimental software, intended for small amounts of eth and the only interaction with Famacoin smart contract on the Ethereum blockchain. Do not expect anything else from fW yet.

fW does not store private keys anywhere. But you must be cautious while using private keys to interact with the Famacoin smart contract when you are both transfering fmc, closing an auction or making a bid.
 
# License
This project is licensed under the MIT license, Copyright (c) 2016 Famacoin, famacoin.org. For more detail see LICENSE.md

