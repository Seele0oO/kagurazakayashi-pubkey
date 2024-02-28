# 🔑 PGP/GPG Pubkey 公钥

`KagurazakaYashi (神楽坂雅詩)`, `KagurazakaMasae (神楽坂雅絵)`

If you want to make sure that no evildoers eavesdrop on data that you send to me, you can use PGP encryption. You can use my public key to encrypt messages so that only I can decrypt them (even you can't decode them). This page describes how to retrieve and verify my PGP public key.

如果你想确保没有坏人窃听你发送给我的数据，你可以使用 PGP 加密。你可以使用我的公钥来加密消息，以便只有我可以解密它们（甚至你自己都无法解密它们）。本页介绍如何检索和验证我的 PGP 公钥。

[![Keybase](https://img.shields.io/badge/-Keybase-33A0FF?logo=Keybase&labelColor=33A0FF&logoColor=fff)](https://keybase.io/kagurazakayashi)

## 📥 Download

### 🔑 [Download Public Key: KagurazakaYashi_2024lts_9CDC44EE8D_public.asc](https://github.com/kagurazakayashi/pubkey/releases/download/2024/KagurazakaYashi_2024lts_9CDC44EE8D_public.asc)

🔏 [Download public key signature file: KagurazakaYashi_2024lts_9CDC44EE8D_public.asc.sig](https://github.com/kagurazakayashi/pubkey/releases/download/2024/KagurazakaYashi_2024lts_9CDC44EE8D_public.asc.sig)

## 📥 下载

### 🔑 [点此下载公钥: KagurazakaYashi_2024lts_9CDC44EE8D_public.asc](https://github.com/kagurazakayashi/pubkey/releases/download/2024/KagurazakaYashi_2024lts_9CDC44EE8D_public.asc)

🔏 [点此下载公钥签名文件: KagurazakaYashi_2024lts_9CDC44EE8D_public.asc.sig](https://github.com/kagurazakayashi/pubkey/releases/download/2024/KagurazakaYashi_2024lts_9CDC44EE8D_public.asc.sig)

## ✅ Verify this repository

🌎 Unique publish and update URL: <https://github.com/kagurazakayashi/pubkey>

1. Go to [commits](https://github.com/kagurazakayashi/pubkey/commits/master) :
2. Check whether the latest Commit has the `verified` label.
3. Click the `verified` label and you should be able to see:
     1. Message: `This commit was signed with the committer’s verified signature.`
     2. `GPG key ID` used when `git commit` : `ED92F99CDC44EE8D` .

[Learn about vigilant mode](https://docs.github.com/github/authenticating-to-github/displaying-verification-statuses-for-all-of-your-commits)

## ✅ 验证此仓库

🌏 唯一指定发布和更新源: <https://github.com/kagurazakayashi/pubkey>

1. 前往 [commits](https://github.com/kagurazakayashi/pubkey/commits/master) ：
2. 检查最新的 Commit 是否具有 `verified` 标签。
3. 点击 verified 标签，应能够看到：
    1. 提示信息： `This commit was signed with the committer’s verified signature.`
    2. `git commit` 时使用的 `GPG key ID` : `ED92F99CDC44EE8D` 。
  
[关于警戒模式](https://docs.github.com/github/authenticating-to-github/displaying-verification-statuses-for-all-of-your-commits)

## 🔐 What is PGP/GPG ?

- [Pretty Good Privacy (PGP)](https://en.wikipedia.org/wiki/Pretty_Good_Privacy) encryption program provides cryptographic privacy and authentication for data communication. PGP is used for signing, encrypting, and decrypting texts, e-mails, files, directories and to increase the security of communications.
- [GNU Privacy Guard (GnuPG or GPG)](https://en.wikipedia.org/wiki/GNU_Privacy_Guard) is a free-software replacement for PGP cryptographic software suite. The software is compliant with RFC 4880, the IETF standards-track specification of OpenPGP.

### ⚙ How does PGP work?

- PGP works based on numerical encryption using public and private keys. For example, when `User A` wants to send an encrypted data to `User B`, the later generates a pair of public and private keys. The private key is kept secret and the public key should be shared with `User A`.
- `User A` encrypts the data using the public key of `User B` and digitally signs the data using the former's private key and sends the data. To decrypt the data, `User B` needs to use the private key associated with the public key used to encrypt the data.

## 🔐 什么是 PGP/GPG ？

- [Pretty Good Privacy (PGP)](https://baike.baidu.com/item/PGP) 加密程序为数据通信提供加密隐私和身份验证。PGP 用于对文本、电子邮件、文件、目录进行签名、加密和解密，并提高通信的安全性。
- [GNU Privacy Guard (GnuPG 或 GPG)](https://baike.baidu.com/item/GnuPG) 是 PGP 加密软件套件的免费软件替代品。该软件符合 OpenPGP 的 IETF 标准 RFC 4880。

### ⚙ 它是如何运作的？

- PGP 基于使用公钥和私钥的数字加密来工作。例如，当 `用户A` 想要向 `用户B` 发送加密数据时，后者生成一对公钥和私钥。私钥保密，公钥应与 `用户A` 共享。
- `用户A` 使用 `用户B` 的公钥对数据进行加密，并使用 `用户B` 的私钥对数据进行数字签名并发送数据。为了解密数据，`用户B` 需要使用与用于加密数据的公钥关联的私钥。

## 🔧 Applications 常用软件

### 💻 Windows / macOS / Linux

If you are not familiar with the commands, you can use the graphical interface software [Kleopatra](https://www.openpgp.org/software/kleopatra/). It is included in:

如果你不熟悉命令，可以使用图形界面软件 [Kleopatra](https://www.openpgp.org/software/kleopatra/) 。它包含在:

- [Gpg4win](https://www.gpg4win.org/) (Windows)
- [GPG Suite](https://gpgtools.org/) (macOS)
- [Kleopatra](https://apps.kde.org/kleopatra/) (Linux KDE)

### 📱 Android / iOS

- [OpenKeychain](https://www.openkeychain.org/) (Android)
- [PGPro](https://pgpro.app/) (iOS)

[More 更多 ...](https://gnupg.org/download/)

## 💻 Common commands 常用命令

These instructions are for `GnuPG (GPG)`, but other `OpenPGP` implementations should work similarly.

这些指令适用于 `GnuPG (GPG)` ，但其他的 `OpenPGP` 实现使用方法应该类似。

### 📁 Key management 密钥管理

- Import the downloaded public key 导入下载的公钥:
  - `gpg --import "KagurazakaYashi_2024lts_9CDC44EE8D_public.asc"`
- Delete a public key 删除一个公钥:
  - `gpg --delete-keys 1F017CCB7C3BFE6CEA4F5D5D3127DF05A772B61D`
- Generate a new key pair 生成你自己的新的密钥对:
  - `gpg --full-generate-key`

### 🔐 Encrypt 加密

- Encrypt a file 加密一个 demo.txt 文件:
  - `gpg -e -r F722E85CBDE9984F192A9E5BED92F99CDC44EE8D -o demo.txt.sig demo.txt`
- Encrypt a text 加密一段文本:
  - `gpg -ea -r F722E85CBDE9984F192A9E5BED92F99CDC44EE8D`
  - `Windows` End input 结束输入: `Ctrl+Z, Enter回车`
  - `macOS` End input 结束输入: `Command+D`
  - `Linux` End input 结束输入: `Ctrl+D`

### 🔏 Sign 签名

- Sign a file 签名一个 demo.txt 文件:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -s -o demo.txt.sig demo.txt`
  - 如果需要独立的文本签名文件可以将 `-s` 改成 `-b -a`
- Sign a text 签名一段文本:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] --clearsign`
- Encrypt and sign a file 加密并签名一个 demo.txt 文件:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -ser F722E85CBDE9984F192A9E5BED92F99CDC44EE8D -o demo.txt.gpg demo.txt`
- Encrypt and sign a text 加密并签名一段文本:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -ser F722E85CBDE9984F192A9E5BED92F99CDC44EE8D -a -e`

### 📖 More commands 更多命令

- `gpg --help`

## 🖋️ Hash 文件校验码

- SHA2-256(KagurazakaYashi_2016lts.rev)
  - `286825c0450a3d366eb29e7105edf5b246ddf3a9d41c9a561270c9ebd993eb99`
- SHA2-256(KagurazakaYashi_2016lts.rev.sig)
  - `c236eab90b9a5f65f04c9fd7e8306cb0eaf45b1a63d8b54a6dab858be633adf3`
- SHA2-256(KagurazakaYashi_2023lts.rev)
  - `2c701609a0fe8e6c56699b2a5464b6a51b93054509754bf2bee4a85fad6b3b32`
- SHA2-256(KagurazakaYashi_2023lts.rev.sig)
  - `40b5582716a27c90498def6715caa6eb73fc77ff8e594516f21de8aa471d1765`
- SHA2-256(KagurazakaYashi_2024lts_9CDC44EE8D_public.asc)
  - `ceff9122ea3b3bb29a0541ae07b64b4f5746c8939eb23f18723ec2ff70c6c593`
- SHA2-256(KagurazakaYashi_2024lts_9CDC44EE8D_public.asc.sig)
  - `3f90afc2aec5275c4a477b112145fab03b376c47101bc04f3b25faa8f0df02e4`

## 🔑 KagurazakaYashi_0xDC44EE8D_public.asc

- Fingerprint 指纹: `F722E85CBDE9984F192A9E5BED92F99CDC44EE8D`
- Valid from 启用日期: `2023/12/13`
- Pubkey URL 公钥服务器:
  - [keyserver.ubuntu.com](https://keyserver.ubuntu.com/pks/lookup?op=get&search=0xF722E85CBDE9984F192A9E5BED92F99CDC44EE8D)
  - [keys.openpgp.org](https://keys.openpgp.org/search?q=F722E85CBDE9984F192A9E5BED92F99CDC44EE8D)
- User IDs 目标用户 ID:
  - Email 电子邮件: `yashi@uuu.moe` (Primary 主显示)
    - Name 用户名: `KagurazakaYashi`
    - Comment 全名: `神楽坂雅詩`
  - Email 电子邮件: `miyabi@uuu.moe`
    - Name 用户名: `KagurazakaMiyabi`
    - Comment 全名: `神楽坂雅詩`
  - Email 电子邮件: `masae@uuu.moe`
    - Name 用户名: `KagurazakaMasae`
    - Comment 全名: `神楽坂雅絵`
  - Email 电子邮件: `admin@uuu.moe`
    - Name 用户名: `Kagurazaka`
    - Comment 全名: `神楽坂`
  - Email 电子邮件: `admin@yashi.moe`
    - Name 用户名: `KagurazakaYashi`
    - Comment 全名: `神楽坂雅詩`
  - Email 电子邮件: `admin@miyabi.moe`
    - Name 用户名: `KagurazakaMiyabi`
    - Comment 全名: `神楽坂雅詩`
  - Email 电子邮件: `admin@masae.moe`
    - Name 用户名: `KagurazakaMasae`
    - Comment 全名: `神楽坂雅絵`
  - Email 电子邮件: `kagurazakayashi@keybase.io`
    - Name 用户名: `keybase.io/kagurazakayashi`
  - Email 电子邮件: `kagurazakayashi@github.com`
    - Name 用户名: `UpdateURL`
    - Comment 全名: `https://github.com/kagurazakayashi/pubkey`
- Subkeys 子密钥:
  - Signature 签名: `F722E85CBDE9984F192A9E5BED92F99CDC44EE8D`
    - Type 加密类型: `EdDSA ed25519`
    - Usage 用途: `Certify 认证, Sign 签名`
  - Signature 签名: `B8A8DF5FB5C7A5E7C5EAD893398AC5505C1469AE`
    - Type 加密类型: `ECDH cv25519`
    - Usage 用途: `Encrypt 加密`
  - Signature 签名: `0BC11CB7DFC838AB6FA779B24C929AA64A31897D`
    - Type 加密类型: `EdDSA ed25519`
    - Usage 用途: `Authenticate 验证`
- OpenPGP v3.4 card
  - Cardholder: `KagurazakaYashi`

```log
sec   ed25519 2023-12-13 [SC]
      F722E85CBDE9984F192A9E5BED92F99CDC44EE8D
uid           [ultimate] KagurazakaYashi (神楽坂雅詩) <yashi@uuu.moe>
uid           [ultimate] KagurazakaMiyabi (神楽坂雅詩) <miyabi@uuu.moe>
uid           [ultimate] KagurazakaMasae (神楽坂雅絵) <masae@uuu.moe>
uid           [ultimate] Kagurazaka (神楽坂) <admin@uuu.moe>
uid           [ultimate] KagurazakaYashi (神楽坂雅詩) <admin@yashi.moe>
uid           [ultimate] KagurazakaMiyabi (神楽坂雅詩) <admin@miyabi.moe>
uid           [ultimate] KagurazakaMasae (神楽坂雅絵) <admin@masae.moe>
uid           [ultimate] [jpeg image of size 4884]
uid           [ultimate] keybase.io/kagurazakayashi <kagurazakayashi@keybase.io>
uid           [ultimate] UpdateURL (https://github.com/kagurazakayashi/pubkey) <kagurazakayashi@github.com>
ssb   cv25519 2023-12-13 [E]
ssb   ed25519 2023-12-13 [A]
```

## 🚫 Revoked Keys 已经作废的密钥对

- These keys have been revoked, please delete and do not use them again.
- 这些密钥已经吊销，请删除并不要再使用。

- `yashipgppublickey2016lts.*`
  - Expire date 到期时间: 2023.10.04
  - Fingerprint 指纹: `1F017CCB7C3BFE6CEA4F5D5D3127DF05A772B61D`
  - Fingerprint 指纹: `501F6F8645F06A4034CCD9B63854E1CA1474714B`
  - Revocation certificate 吊销证书: [KagurazakaYashi_2016lts.rev](https://github.com/kagurazakayashi/pubkey/releases/download/2024/KagurazakaYashi_2016lts.rev)
- `yashipgppublickey2023lts.*`
  - Expire date 到期时间: 2023.12.31
  - Fingerprint 指纹: `9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3`
  - Revocation certificate 吊销证书: [KagurazakaYashi_2023lts.rev](https://github.com/kagurazakayashi/pubkey/releases/download/2024/KagurazakaYashi_2023lts.rev)
