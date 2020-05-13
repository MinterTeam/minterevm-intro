# MinterEVM

**WARNING**: MinterEVM is under VERY ACTIVE DEVELOPMENT and should be treated as pre-alpha software. This means it is not meant to be run in production, its APIs are subject to change without warning and should not be relied upon, and it should not be used to hold any value. We will remove this warning when we have a release that is stable, secure, and properly tested.

## How to Connect
1. [Download](https://github.com/MyEtherWallet/MyEtherWallet/releases/tag/v5.6.1) `MyEtherWallet`, unpack archive and launch it by opening  `index.html` in your browser.
2. Log In using `mnemonic phrase` or `private key`.
3. In `Network` block click `Change` and then add Custom Node with this params:
- ETH Node Name: `MinterEVM`
- URL: `https://testnet.evm-node.minter.network`
- Port: `433`
- Chain ID: `8`
4. Choose created custom network.
5. Now you have access to your MinterEVM wallet.

<img src="/mew_settings.png" width="400">

## How to Send MNT to MinterEVM
1. Log Into [Minter Testnet Console](https://testnet.console.minter.network/).
2. Send any amount of MNT to `Mxe58b691fda89931b17c0d988a9288e1284220c1b` with payload containing your  EVM address.
3. Coins should be credited to your MinterEVM address in a few seconds. 

<img src="/send_mnt.png">

## How to Get MNT back from MinterEVM
1. Log Into MyEtherWallet.
2. Send any amount of coins to  `0x0000000000000000000000000000000000000000` with `Data` containing your Minter Testnet Address (replace Mx with 0x).
3. Coins should be credited to your Minter Testnet address in a few seconds.

<img src="/withdraw_mnt.png" width="600">
