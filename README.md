# pytoniq-core

This is a fork of [pytoniq-core](https://github.com/yungwine/pytoniq-core). It extends compatibility to Python 3.7, 3.8, and 3.9, as the original package strictly requires Python >= 3.10.

[![PyPI version](https://badge.fury.io/py/pytoniq-core-fork.svg)](https://badge.fury.io/py/pytoniq-core-fork)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/pytoniq-core-fork)](https://pypi.org/project/pytoniq-core-fork/)
[![Python package](https://github.com/ebellocchia/pytoniq-core/actions/workflows/python-package.yml/badge.svg)](https://github.com/ebellocchia/pytoniq-core/actions/workflows/python-package.yml)
[![](https://img.shields.io/badge/%F0%9F%92%8E-TON-grey)](https://ton.org)

---

## Installation

```bash
pip install pytoniq-core-fork
```

## Examples

You can find them in the [/examples](/examples) folder.

## Donations

TON - `EQBvW8Z5huBkMJYdnfAEM5JqTNkuWX3diqYENkWsIL0XggGG`

## Structure

### boc

* Cell
* Slice
* Builder
* Hashmap
* Address
* Exotic cells

### crypto

* Cryptography for ADNL
* Native fast crc functions
* Keys, Mnemonics generation
* Signatures creation and verifying

### proof

* Merkle proofs verifying - [article](https://docs.ton.org/develop/data-formats/proofs)

### tl

* [TL](https://core.telegram.org/mtproto/TL) automatic (de)serialization

### tl-b

* Almost all wrappers for schemes from [block.tlb](https://github.com/ton-blockchain/ton/blob/master/crypto/block/block.tlb)
* Classes for popular custom tlb schemes
