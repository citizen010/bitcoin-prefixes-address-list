![Bitcoin](https://img.shields.io/badge/bitcoin-btc-orange) ![MIT license](https://img.shields.io/badge/license-MIT-blue)

# Bitcoin address format

A Bitcoin address is an identifier (like an account number), starting with 1, 3 or bc1 on the mainnet, containing 27-34 alphanumeric Latin characters and digits (except 0, O, I).

# Full list of Bitcoin address prefixes

A __Bitcoin address__, or simply __address__, is an identifier of 27-34 alphanumeric characters, beginning with the number 1, 3 or bc1, that represents a possible destination for a bitcoin payment. Addresses can be generated at no cost by any user of Bitcoin. It is also possible to get a Bitcoin address using an account at an exchange or online wallet service. Also, you can generate it offline and store on paper or at any digital storage.

There are currently four address formats in use in Bitcoin mainnet:

1. P2PKH (Pay 2 Public Key Hash) which begin with the number 1
2. P2SH (Pay 2 Script Hash) type starting with the number 3.
3. [Bech32](https://en.bitcoin.it/wiki/Bech32) type starting with bc1.
4. [Taproot](https://github.com/bitcoin/bips/blob/master/bip-0341.mediawiki) type starting with bc1p.

Example use | Leading symbol(s) | Example
----------- | :---------------: | -------
Pubkey hash ([P2PKH address](https://en.bitcoin.it/wiki/Transaction#Pay-to-PubkeyHash)) | 1 | 17VZNX1SN5NtKa8UQFxw ...
Script hash ([P2SH address](https://en.bitcoin.it/wiki/Pay_to_script_hash)) | 3 | 3EktnHQD7RiAE6uzMj2Z ...
SegWit mainnet ([P2WPKH address](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki)) | bc1 | bc1qw508d6qejxtdg4y5 ...
SegWit Testnet ([P2WPKH address](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki)) | tb1 | tb1qw508d6qejxtdg4y5 ...
SegWit mainnet ([P2WSH address](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki)) | bc1 | bc1qrp33g0q5c5txsp9a ...
SegWit Testnet ([P2WSH address](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki)) | tb1 | tb1qrp33g0q5c5txsp9a ...
Private key ([WIF](https://en.bitcoin.it/wiki/Wallet_import_format), uncompressed pubkey) | 5 | 5Hwgr3u458GLafKBgxts ...
Private key ([WIF](https://en.bitcoin.it/wiki/Wallet_import_format), compressed pubkey) | K _or_ L | L1aW4aubDFB7yfras2S1 ...
[BIP32](https://en.bitcoin.it/wiki/BIP_0032) pubkey | xpub | xpub661MyMwAqRbcEYS8 ...
[BIP49](https://en.bitcoin.it/wiki/BIP_0049) pubkey | ypub | ypub6XiW9nhToS1gjVsF ...
[BIP49](https://en.bitcoin.it/wiki/BIP_0049) pubkey | zpub | zpub6qeoQyhseR78SC69 ...
[BIP32](https://en.bitcoin.it/wiki/BIP_0032) private key | xprv | xprv9s21ZrQH143K24Mf ...
Testnet pubkey hash | m _or_ n | mipcBbFg9gMiCh81Kj8t ...
Testnet script hash | 2 | 2MzQwSSnBHWHqSAqtTVQ ...
Testnet Private key (WIF, uncompressed pubkey) | 9 | 92Pg46rUhgTT7romnV7i ...
Testnet Private key (WIF, compressed pubkey) | c | cNJFgo1driFnPcBdBX8B ...
Testnet BIP32 pubkey | tpub | tpubD6NzVbkrYhZ4WLcz ...
Testnet BIP32 private key | tprv | tprv8ZgxMBicQKsPcsbC ...
RegTest BIP32 address | brct1 | bcrt1q4gfcga7jfjmm02 ...

# Hierarchical Deterministic Wallet

A HD wallet, or [hierarchical deterministic](https://en.bitcoin.it/wiki/Deterministic_wallet) wallet is a system of deriving keys from a single starting point known as a seed. The seed allows a user to easily back up and restore a wallet without needing any other information and can in some cases allow the creation of public addresses without the knowledge of the private key. Seeds are typically serialized into human-readable words in a Seed phrase. 
