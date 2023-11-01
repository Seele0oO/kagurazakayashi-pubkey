# 🔑 PGP/GPG Pubkey 公钥

`KagurazakaYashi (神楽坂雅詩)`, `KagurazakaMasae (神楽坂雅絵)`

If you want to make sure that no evildoers eavesdrop on data that you send to me, you can use PGP encryption. You can use my public key to encrypt messages so that only I can decrypt them (even you can't decode them). This page describes how to retrieve and verify my PGP public key.

如果你想确保没有坏人窃听你发送给我的数据，你可以使用 PGP 加密。你可以使用我的公钥来加密消息，以便只有我可以解密它们（甚至你自己都无法解密它们）。本页介绍如何检索和验证我的 PGP 公钥。

[![Keybase](https://img.shields.io/badge/-Keybase-33A0FF?logo=Keybase&labelColor=33A0FF&logoColor=fff)](https://keybase.io/kagurazakayashi)

## 📥 Download

### 🔑 [Download Public Key: KagurazakaYashi_2023lts_0xB8C957F3_public.asc](https://github.com/kagurazakayashi/pubkey/releases/download/2023.10/KagurazakaYashi_2023lts_0xB8C957F3_public.asc)

🔏 [Download public key signature file: KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig](https://github.com/kagurazakayashi/pubkey/releases/download/2023.10/KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig)

## 📥 下载

### 🔑 [点此下载公钥: KagurazakaYashi_2023lts_0xB8C957F3_public.asc](https://github.com/kagurazakayashi/pubkey/releases/download/2023.10/KagurazakaYashi_2023lts_0xB8C957F3_public.asc)

🔏 [点此下载公钥签名文件: KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig](https://github.com/kagurazakayashi/pubkey/releases/download/2023.10/KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig)

## ✅ Verify this repository

🌎 Unique publish and update URL: <https://github.com/kagurazakayashi/pubkey>

1. Go to [commits](https://github.com/kagurazakayashi/pubkey/commits/master) :
2. Check whether the latest Commit has the `verified` label.
3. Click the `verified` label and you should be able to see:
     1. Message: `This commit was signed with the committer’s verified signature.`
     2. `GPG key ID` used when `git commit` : `79A9CCDDB8C957F3` .

[Learn about vigilant mode](https://docs.github.com/github/authenticating-to-github/displaying-verification-statuses-for-all-of-your-commits)

## ✅ 验证此仓库

🌏 唯一指定发布和更新源: <https://github.com/kagurazakayashi/pubkey>

1. 前往 [commits](https://github.com/kagurazakayashi/pubkey/commits/master) ：
2. 检查最新的 Commit 是否具有 `verified` 标签。
3. 点击 verified 标签，应能够看到：
    1. 提示信息： `This commit was signed with the committer’s verified signature.`
    2. `git commit` 时使用的 `GPG key ID` : `79A9CCDDB8C957F3` 。
  
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
  - `gpg --import "KagurazakaYashi_2023lts_0xB8C957F3_public.asc"`
- Delete a public key 删除一个公钥:
  - `gpg --delete-keys 1F017CCB7C3BFE6CEA4F5D5D3127DF05A772B61D`
- Generate a new key pair 生成你自己的新的密钥对:
  - `gpg --full-generate-key`

### 🔐 Encrypt 加密

- Encrypt a file 加密一个 demo.txt 文件:
  - `gpg -e -r 9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3 -o demo.txt.sig demo.txt`
- Encrypt a text 加密一段文本:
  - `gpg -ea -r 9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3`
  - `Windows` End input 结束输入: `Ctrl+Z, Enter回车`
  - `macOS` End input 结束输入: `Command+D`
  - `Linux` End input 结束输入: `Ctrl+D`

### 🔏 Sign 签名

- Sign a file 签名一个 demo.txt 文件:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -s -o demo.txt.sig demo.txt`
- Sign a text 签名一段文本:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] --clearsign`
- Encrypt and sign a file 加密并签名一个 demo.txt 文件:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -ser 9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3 -o demo.txt.gpg demo.txt`
- Encrypt and sign a text 加密并签名一段文本:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -ser 9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3 -a -e`

### 📖 More commands 更多命令

- `gpg --help`

## 🖋️ Hash 文件校验码

```ini
[openssl md5 KagurazakaYashi_2023*]
MD5(KagurazakaYashi_2023lts_0xB8C957F3_public.asc)= "b66dd5b045e8a7f904eda2364044a9ec"
MD5(KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig)= "bcc222e1c8eabe4cfe009c3631eca533"
[openssl sha256 KagurazakaYashi_2023*]
SHA2-256(KagurazakaYashi_2023lts_0xB8C957F3_public.asc)= "7fd7d500f139e912f7c7ae53a79637b19ab6b475443908d3e02227d838318bbe"
SHA2-256(KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig)= '94ba292c8c67f22dcaa04dea2e27419a5e94b70dece8d1378d5d6dc9844bc241'
```

## 🔑 KagurazakaYashi_0xB8C957F3_public.asc

- Fingerprint 指纹: `9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3`
- Key-ID 公钥ID: `79A9CCDDB8C957F3`
- Valid from 启用日期: `2023/9/26`
- Pubkey URL 公钥服务器: [keyserver.ubuntu.com](https://keyserver.ubuntu.com/pks/lookup?op=get&search=0x9a9121afe0002ab746fb0b1079a9ccddb8c957f3)
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
  - Email 电子邮件: `kagurazakayashi@keybase.io`
    - Name 用户名: `keybase.io/kagurazakayashi`
  - Email 电子邮件: `admin@uuu.moe`
    - Name 用户名: `admin.uuu.moe`
  - Email 电子邮件: `administrator@uuu.moe`
    - Name 用户名: `administrator.uuu.moe`
  - Email 电子邮件: `hostmaster@uuu.moe`
    - Name 用户名: `hostmaster.uuu.moe`
  - Email 电子邮件: `webmaster@uuu.moe`
    - Name 用户名: `webmaster.uuu.moe`
  - Email 电子邮件: `postmaster@uuu.moe`
    - Name 用户名: `postmaster.uuu.moe`
- Subkeys 子密钥:
  - ID 编号: `79A9CCDDB8C957F3`
    - Signature 签名: `9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3`
    - Type 加密类型: `RSA 4096`
    - Usage 用途: `Certify 认证, Sign 签名`
  - ID 编号: `B1DD0AD34E9E53AD`
    - Authentication 验证: `F92E1E75887C744638181A20B1DD0AD34E9E53AD`
    - Type 加密类型: `RSA 4096`
    - Usage 用途: `Authenticate 验证`
  - ID 编号: `AA09F84D08FBCBD7`
    - Encryption 加密: `EC034D6C3F7417663A0DE830AA09F84D08FBCBD7`
    - Type 加密类型: `RSA 4096`
    - Usage 用途: `Encrypt 加密`
- OpenPGP v3.4 card (本次私钥采用智能卡硬件保存)
  - Cardholder: `KagurazakaYashi`

```log
sec   rsa4096 2023-09-26 [SC]
      9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3
uid           KagurazakaYashi (神楽坂雅詩) <yashi@uuu.moe>
uid           KagurazakaMiyabi (神楽坂雅詩) <miyabi@uuu.moe>
uid           KagurazakaMasae (神楽坂雅絵) <masae@uuu.moe>
uid           [jpeg image of size 4884]
uid           admin.uuu.moe <admin@uuu.moe>
uid           administrator.uuu.moe <administrator@uuu.moe>
uid           hostmaster.uuu.moe <hostmaster@uuu.moe>
uid           webmaster.uuu.moe <webmaster@uuu.moe>
uid           postmaster.uuu.moe <postmaster@uuu.moe>
uid           keybase.io/kagurazakayashi <kagurazakayashi@keybase.io>
ssb   rsa4096 2023-09-26 [E]
ssb   rsa4096 2023-09-26 [A]
```

## 🚫 Revoked Keys 已经作废的密钥对

- These keys have been revoked, please delete and do not use them again.
- 这些密钥已经吊销，请删除并不要再使用。

### `yashipgppublickey2016lts.asc`, `yashisshpublickey2016lts.pub`

- 🔓 Revocation certificate 吊销证书:
  - [KagurazakaYashi_2016lts.rev](https://github.comkagurazakayashi/pubkey/releases/download/2023.10/KagurazakaYashi_2016lts.rev)
- Fingerprint 指纹: `1F017CCB7C3BFE6CEA4F5D5D3127DF05A772B61D`, `501F6F8645F06A4034CCD9B63854E1CA1474714B`
  - pub rsa4096/`501f6f8645f06a4034ccd9b63854e1ca1474714b` 2016-06-26T05:12:38Z
  - sig revok `3854e1ca1474714b` 2016-06-26T05:12:41Z
  - pub rsa4096/`1f017ccb7c3bfe6cea4f5d5d3127df05a772b61d` 2016-09-11T16:51:51Z
  - sig revok `3127df05a772b61d` 2023-09-26T06:14:52Z
  - sub rsa4096/`0b32ef63d918d12c2e5ea4d7ed973e251f29634c` 2016-06-26T05:12:38Z
