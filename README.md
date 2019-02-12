# miner

A proof of concept Arionum miner.

## Install

**Requirements:**

- PHP 7.2
  - GMP extension
  - OpenSSL extension

## Usage

**For solo mining:**

The miner's IP must be added in the node's allowed hosts.

```bash
miner solo [node] [public_key] [private_key]
```

**For pool mining:**

```bash
miner pool http://aropool.com [address]
```

## Development Fund

Coin | Address
---- | --------
[ARO]: | 5WuRMXGM7Pf8NqEArVz1NxgSBptkimSpvuSaYC79g1yo3RDQc8TjVtGH5chQWQV7CHbJEuq9DmW5fbmCEW4AghQr
[LTC]: | LWgqzbXGeucKaMmJEvwaAWPFrAgKiJ4Y4m
[BTC]: | 1LdoMmYitb4C3pXoGNLL1VRj7xk3smGXoU
[ETH]: | 0x4B904bDf071E9b98441d25316c824D7b7E447527
[BCH]: | qrtkqrl3mxzdzl66nchkgdv73uu3rf7jdy7el2vduw

If you'd like to support the Arionum development, you can donate to the addresses listed above.

[aro]: https://arionum.com
[ltc]: https://litecoin.org
[btc]: https://bitcoin.org
[eth]: https://ethereum.org
[bch]: https://www.bitcoincash.org
