# Crypto Wallet Finder: Unlock Your Lost Digital Assets with WalletGen

**Lost access to your crypto?**  **WalletGen** is a powerful, open-source solution designed to help you find and potentially recover lost or inactive **Bitcoin (BTC)**, **Ethereum (ETH)**, **BNB**, **Polygon (MATIC)**, and other **EVM-compatible wallets**. It's a rapid, efficient **crypto wallet finder** and **seed phrase brute force tool**, built on a high-performance C++ engine.

<!--
Meta description:
WalletGen - Your ultimate crypto wallet finder. Open-source, high-speed tool to recover lost Bitcoin, Ethereum, and EVM-compatible wallets. Brute-force seed recovery & balance checks. Download now!
-->

## Quick Navigation
- [How It Works: The Inner Workings of WalletGen](#how-it-works)
- [Why Choose WalletGen for Finding Wallets?](#why-walletgen)
- [Key Features: What Sets WalletGen Apart](#features)
- [Get Started: Downloading WalletGen](#how-to-start)
- [Boost Your Search: Database Downloads](#download-and-use-database-for-more-speed)
- [Wallet Found! What to Do Next](#the-program-found-a-wallet--whats-next)
- [Recovering Your Bitcoin: A Detailed Guide](#recovery-your-bitcoin-wallet)
- [Real-World Results: My Finds and Success Stories](#my-finds)
- [Frequently Asked Questions (FAQ)](#-frequently-asked-questions-faq)
- [Build Instructions: Compiling the Project](#building-the-project)
- [Support the Project: Donate](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="wallet finder crypto" title="WalletGen wallet generator" height="460" src="/content/explorer.webp" />
</p>

⚠️ **Important Note**:  WalletGen is strictly for research and educational use. It is *not* intended for unauthorized access or malicious activities. Please use it responsibly and only with wallets you own or have explicit permission to access.

## How It Works

WalletGen leverages industry-standard protocols such as [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), [BIP44](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), and [Bech32](https://en.bitcoin.it/wiki/Bech32) for Bitcoin wallet generation.  For EVM-based chains like Ethereum, the software utilizes the [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing algorithm.

The core functionality involves generating a multitude of potential wallet addresses and verifying their balances. This is achieved either through real-time balance checks via public blockchain explorers or, more efficiently, by comparing generated addresses against a pre-built database of known addresses with existing funds. WalletGen's C++ foundation results in significantly faster wallet generation speeds compared to many Python-based alternatives, with the performance primarily dependent on your CPU and GPU.

## Why Choose WalletGen?

Why wait? **WalletGen** is engineered for speed and efficiency.  Unlike slower, Python-based tools, this wallet finder is written in C++ and optimized for multi-threaded CPU and GPU usage, resulting in up to **10x faster** performance. If you are exploring lost wallets, verifying private key spaces, or striving to recover access to your crypto holdings, WalletGen equips you with the speed, efficiency, and security to do it successfully.

## Features

-   **Crypto Wallet Generation**:  WalletGen allows you to create wallets for Bitcoin, Ethereum, BNB, MATIC, and other popular cryptocurrencies.
-   **Balance Finding through Brute-Force**:  Use advanced brute-force methods to search for wallets that contain balances on both the Bitcoin network and EVM-compatible blockchains.
-   **Algorithm Support**:  WalletGen utilizes Keccak256 for EVM wallets and BIP39, BIP44, and Bech32 for Bitcoin, guaranteeing widespread compatibility.
-   **Database Integration**: Download and use databases to significantly increase your search speed, making the process much faster.
-   **Blazing Fast Performance**:  WalletGen harnesses your CPU and GPU to deliver peak performance.
-   **Bitcoin Wallet Recovery by Seed Phrase**:  Recover your Bitcoin wallet with ease using your mnemonic seed phrase.

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Windows Demo" title="WalletGen search lost bitcoin wallets on Windows" src="/content/board.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Linux Demo" title="WalletGen search lost bitcoin wallets on Linux" src="/content/restore.webp" />
</p>

# How to start

## Windows
-   Download [Release](../../releases)
-   Unpack anywhere
-   Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget
or download [Release for Linux](../../releases)




## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** provides two primary methods to scan for crypto wallets that contain a balance, using brute-force techniques.

### Finding Bitcoin (BTC) Wallets:

*   Start by pressing key `3` in the menu or run the `start_search_btc.bat` file. This will initiate an internet-based search for Bitcoin wallets. Keep in mind that this method may take more time, since it checks wallet balances in real-time via blockchain explorers.
*   For quicker results, press key `6` to search for Bitcoin wallets using the included database. This method is much faster, as it compares generated wallets against a pre-existing database of known addresses and balances.

### Searching for EVM Wallets (Ethereum, BNB, MATIC, etc.):

*   To begin, press key `5` or run `start_search_evm.bat` to initiate an internet-based search for EVM wallets. This method checks for wallet balances in real-time using blockchain explorers.
*   To speed up the process, use key `6` to search EVM wallets using the available database. This is the more rapid option because it compares generated wallets against a known database of addresses that contain balances.

### Important Speed Factors:

*   The speed of the search is largely influenced by your hardware, especially your graphics card (GPU). To enhance performance and raise your chances of finding a wallet with a balance, consider running multiple program instances concurrently (1 to 4), which will depend on your system's capabilities.

By utilizing a database, you'll significantly streamline the search process, removing the need to continuously query the blockchain for every newly generated wallet, thus enhancing efficiency.

## The Program Found a Wallet — What’s Next?

When WalletGen finds a wallet with a balance, it will:
*   **Immediately Stop** the search.
*   **Display** the wallet details right in the console window.
*   **Save** all the important data to the `found_wallets.txt` file.

### How to Access the Funds?

1.  Use the found **mnemonic seed phrase** to import the wallet into a compatible crypto wallet (such as Metamask, Trust Wallet, or Electrum).
2.  Once the wallet is restored, you will be able to transfer the funds to a wallet you control.

>  If your search is successful, consider supporting the project by sharing a small portion of the recovered balance!

## Recovery Your Bitcoin Wallet

WalletGen is designed to aid in Bitcoin wallet recovery by using a seed phrase (mnemonic phrase). It supports both the full seed phrase and the use of special characters to look for missing words.

### Process Overview

#### Finding Missing Words:

If some words are missing from your seed phrase, replace those missing words with an asterisk (*). WalletGen will search through all possible combinations for the * positions in order to find the correct seed phrase and, hopefully, restore your wallet.

#### Entering the Full Seed Phrase:

If you have the complete 12-word seed, input it in its entirety, separating each word with a space. WalletGen will generate all address types (Legacy, SegWit, P2SH) and check for balances.

![recovery](/content/desktop.webp)

### Important Recommendations

*   Seed phrases must always consist of 12 words.
*   Use only the asterisk (*) symbol to denote missing words.
*   Remember that searching for missing words can take a significant amount of time, particularly if multiple words are missing.
*   Upon successful recovery of a wallet containing a balance, the program will automatically stop and store all the relevant data.

## My Finds

![mywallet](/content/progress.webp)

I've successfully recovered two BTC wallets with a balance. The first had 0.000032 BTC, and the second held 0.0528 BTC (around $4800 at the time).
Here's the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/content/stop.webp" />
</p>

### Latest Find 4/9/2025

After a week of non-stop wallet scanning, I found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is the biggest find yet!

![image](/content/default.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/content/archive.webp)

## Building the Project

1.  Open the project file (`CryptoWalletGen.sln`) using Visual Studio or a compatible C++ compiler.
2.  Ensure you have installed and configured the required dependencies for the project to build.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3.  Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ How do I get WalletGen?
You can download WalletGen from the [release download page](../../releases).

### ❓ Where can I download the database of known addresses?
You can find the latest database on the [release page](../../releases).

### ❓ Can WalletGen help recover my lost Bitcoin wallet?
Yes, WalletGen uses brute-force seed phrase generation and a known-address database to assist in **recovering lost Bitcoin wallets**.

### ❓ Is WalletGen a seed phrase generator?
Yes, WalletGen can generate **BIP39 seed phrases** and derive wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Does database searching require an internet connection?
No, you don't need an internet connection for searching the database; the balance information is already known.

### ❓ Can I search for Ethereum wallets with a balance?
Yes, WalletGen supports scanning for **Ethereum wallets with a balance** using brute-force techniques and an address database.

### ❓ Is WalletGen legal?
WalletGen is intended for **educational and research purposes only**. Use it *only* on wallets you own or have permission to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

Contributions are highly appreciated! If you have ideas, find bugs, or want to contribute to the code, submit a pull request.

## Donate

If you find a wallet with a balance, consider sending a small portion as a thank you! This supports ongoing development and improvements to the tool.

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)



Update:  06/13/2025 04-29-14