# Full list of Bitcoin address prefixes

A __Bitcoin address__, or simply __address__, is an identifier of 27-34 alphanumeric characters, beginning with the number 1, 3 or bc1, that represents a possible destination for a bitcoin payment. Addresses can be generated at no cost by any user of Bitcoin. It is also possible to get a Bitcoin address using an account at an exchange or online wallet service. Also you can generate it offline and store on paper or at any digital storage.

There are currently three address formats in use in Bitcoin mainnet:

1. P2PKH (Pay 2 Public Key Hash) which begin with the number 1
2. P2SH (Pay 2 Script Hash) type starting with the number 3.
3. [Bech32](https://en.bitcoin.it/wiki/Bech32) type starting with bc1.

<style>
td {font-size: 8px;}
</style>

Example use | Leading symbol(s) | Example
----------- | :---------------: | -------
Pubkey hash ([P2PKH address](https://en.bitcoin.it/wiki/Transaction#Pay-to-PubkeyHash)) | 1 | 17VZNX1SN5NtKa8UQFxwQbFeFc3iqRYhem
Script hash ([P2SH address](https://en.bitcoin.it/wiki/Pay_to_script_hash)) | 3 | 3EktnHQD7RiAE6uzMj2ZifT9YgRrkSgzQX
SegWit mainnet ([P2WPKH address](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki)) | bc1 | bc1qw508d6qejxtdg4y5r3zarvary0c5xw7kv8f3t4
SegWit Testnet ([P2WPKH address](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki)) | tb1 | tb1qw508d6qejxtdg4y5r3zarvary0c5xw7kxpjzsx
SegWit mainnet ([P2WSH address](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki)) | bc1 | bc1qrp33g0q5c5txsp9arysrx4k6zdkfs4nce4xj0gdcccefvpysxf3qccfmv3
SegWit Testnet ([P2WSH address](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki)) | tb1 | tb1qrp33g0q5c5txsp9arysrx4k6zdkfs4nce4xj0gdcccefvpysxf3q0sl5k7
Private key ([WIF](https://en.bitcoin.it/wiki/Wallet_import_format), uncompressed pubkey) | 5 | 5Hwgr3u458GLafKBgxtssHSPqJnYoGrSzgQsPwLFhLNYskDPyyA
Private key ([WIF](https://en.bitcoin.it/wiki/Wallet_import_format), compressed pubkey) | K or L | L1aW4aubDFB7yfras2S1mN3bqg9nwySY8nkoLmJebSLD5BWv3ENZ
[BIP32](https://en.bitcoin.it/wiki/BIP_0032) pubkey | xpub |  	xpub661MyMwAqRbcEYS8w7XLSVeEsBXy79zSzH1J8vCdxAZningWLdN3zgtU6LBpB85b3D2yc8sfvZU521AAwdZafEz7mnzBBsz4wKY5e4cp9LB
[BIP32](https://en.bitcoin.it/wiki/BIP_0032) private key | xprv |  	xprv9s21ZrQH143K24Mfq5zL5MhWK9hUhhGbd45hLXo2Pq2oqzMMo63oStZzF93Y5wvzdUayhgkkFoicQZcP3y52uPPxFnfoLZB21Teqt1VvEHx
Testnet pubkey hash | m or n | mipcBbFg9gMiCh81Kj8tqqdgoZub1ZJRfn
Testnet script hash | 2 | 2MzQwSSnBHWHqSAqtTVQ6v47XtaisrJa1Vc
Testnet Private key (WIF, uncompressed pubkey) | 9 | 92Pg46rUhgTT7romnV7iGW6W1gbGdeezqdbJCzShkCsYNzyyNcc
Testnet Private key (WIF, compressed pubkey) | c | cNJFgo1driFnPcBdBX8BrJrpxchBWXwXCvNH5SoSkdcF6JXXwHMm
Testnet BIP32 pubkey | tpub |  	tpubD6NzVbkrYhZ4WLczPJWReQycCJdd6YVWXubbVUFnJ5KgU5MDQrD998ZJLNGbhd2pq7ZtDiPYTfJ7iBenLVQpYgSQqPjUsQeJXH8VQ8xA67D
Testnet BIP32 private key | tprv | tprv8ZgxMBicQKsPcsbCVeqqF1KVdH7gwDJbxbzpCxDUsoXHdb6SnTPYxdwSAKDC6KKJzv7khnNWRAJQsRA8BBQyiSfYnRt6zuu4vZQGKjeW4YF
