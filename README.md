# 🔑 GPG Pubkey 公钥

KagurazakaYashi (神楽坂雅詩), KagurazakaMasae (神楽坂雅絵)

- **This is the pubkey in case you need.**
- **这里是我的 GPG 公钥，如果你想和我加密通讯，可能会需要它。**

## 📥 Download 下载

- **[![Pubkey URL](https://img.shields.io/badge/-PGPkey-0093DD?logo=GNU%20Privacy%20Guard&labelColor=0093DD&logoColor=fff) Download Public Key 点此下载公钥: KagurazakaYashi_2023lts_0xB8C957F3_public.asc](https://github.com/kagurazakayashi/pubkey/releases/download/2023.10/KagurazakaYashi_2023lts_0xB8C957F3_public.asc)**
  - [Download public key signature file 点此下载公钥签名文件: KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig](https://github.com/kagurazakayashi/pubkey/releases/download/2023.10/KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig)

- **Unique publish and update URL 唯一指定发布和更新源:**
  - <https://github.com/kagurazakayashi/pubkey>

## 🔐 What is GPG ? 什么是 GPG ？

- [Pretty Good Privacy (PGP)](https://en.wikipedia.org/wiki/Pretty_Good_Privacy) encryption program provides cryptographic privacy and authentication for data communication. PGP is used for signing, encrypting, and decrypting texts, e-mails, files, directories and to increase the security of communications.
  - [GNU Privacy Guard (GnuPG or GPG)](https://en.wikipedia.org/wiki/GNU_Privacy_Guard) is a free-software replacement for PGP cryptographic software suite. The software is compliant with RFC 4880, the IETF standards-track specification of OpenPGP.
- [Pretty Good Privacy (PGP)](https://baike.baidu.com/item/PGP) 加密程序为数据通信提供加密隐私和身份验证。 PGP 用于对文本、电子邮件、文件、目录进行签名、加密和解密，并提高通信的安全性。
  - [GNU Privacy Guard (GnuPG 或 GPG)](https://baike.baidu.com/item/GnuPG) 是 PGP 加密软件套件的免费软件替代品。 该软件符合 OpenPGP 的 IETF 标准轨道规范 RFC 4880。

## 📱 Applications 常用软件

- If you are not familiar with the commands, you can use the graphical interface software [Kleopatra](https://www.openpgp.org/software/kleopatra/). It is included in:
- 如果你不熟悉命令，可以使用图形界面软件 [Kleopatra](https://www.openpgp.org/software/kleopatra/) 。它包含在:
  - [Gpg4win](https://www.gpg4win.org/) (Windows)
  - [GPG Suite](https://gpgtools.org/) (macOS)
  - [Kleopatra](https://apps.kde.org/kleopatra/) (Linux KDE)
- Mobile apps 手机 APP :
  - [OpenKeychain](https://www.openkeychain.org/) (Android)
  - [PGPro](https://pgpro.app/) (iOS)
- [More 更多 ...](https://gnupg.org/download/)

## 💻 Common commands 常用命令

### Key management 密钥管理

- Import the downloaded public key 导入下载的公钥:
  - `gpg --import "KagurazakaYashi_2023lts_0xB8C957F3_public.asc"`
- Delete a public key 删除一个公钥:
  - `gpg --delete-keys 1F017CCB7C3BFE6CEA4F5D5D3127DF05A772B61D`
- Generate a new key pair 生成你自己的新的密钥对:
  - `gpg --full-generate-key`

### Encrypt 加密

- Encrypt a file 加密一个文件:
  - `gpg -e -r 9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3 demo.txt`
  - output 生成文件: `demo.txt.gpg`
- Encrypt a text 加密一段文本:
  - `gpg -ea -r 9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3`
  - `Windows` End input 结束输入: `Ctrl+Z, Enter回车`
  - `macOS` End input 结束输入: `Command+D`
  - `Linux` End input 结束输入: `Ctrl+D`

### Sign 签名

- Sign a file 签名一个文件:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -s demo.txt`
  - output 生成文件: `demo.txt.asc`
- Sign a text 签名一段文本:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] --clearsign`
- Encrypt and sign a file 加密并签名一个文件:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -ser 9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3 1.txt`
- Encrypt and sign a text 加密并签名一段文本:
  - `gpg -u [Your private key fingerprint 你的私钥指纹] -ser 9A9121AFE0002AB746FB0B1079A9CCDDB8C957F3 -a 1.txt`

### More commands 更多命令

- `gpg --help`

## 🖋️ Hash 文件校验码

```ini
[openssl md5 K*]
KagurazakaYashi_2016lts.rev="b312667712c4321f120f6f619d96f341"
KagurazakaYashi_2023lts_0xB8C957F3_public.asc="20394805a05aca8e9254b4d76e0e7f67"
KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig="66fa7155a50068fd1d3d3a3f2dae989f"
[openssl sha1 K*]
KagurazakaYashi_2016lts.rev="f3c3452afd8852316d096f307c7378e9ccae1016"
KagurazakaYashi_2023lts_0xB8C957F3_public.asc="6dbacdd7c92608823109ecf375617f66dc402073"
KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig="58060a608c585739e23a2eaf4307fbbbd328df8a"
[openssl sha256 K*]
KagurazakaYashi_2016lts.rev="286825c0450a3d366eb29e7105edf5b246ddf3a9d41c9a561270c9ebd993eb99"
KagurazakaYashi_2023lts_0xB8C957F3_public.asc="a3e2457b2c67676aa3e74036bbc0624ee83b3a2bcec7f48de5bf03ded45de41f"
KagurazakaYashi_2023lts_0xB8C957F3_public.asc.sig="5e5838757a0a121a4ecb2314503b6b07e15f88f3d5be9db2f3725bd77d9010d1"
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
pub   rsa4096 2023-09-26 [SC]
      9A91 21AF E000 2AB7 46FB  0B10 79A9 CCDD B8C9 57F3
uid           [ultimate] KagurazakaYashi (神楽坂雅詩) <yashi@uuu.moe>
sig 3        79A9CCDDB8C957F3 2023-09-26  [self-signature]
uid           [ultimate] KagurazakaMasae (神楽坂雅絵) <masae@uuu.moe>
sig 3        79A9CCDDB8C957F3 2023-09-26  [self-signature]
uid           [ultimate] KagurazakaMiyabi (神楽坂雅詩) <miyabi@uuu.moe>
sig 3        79A9CCDDB8C957F3 2023-09-26  [self-signature]
uid           [ultimate] [jpeg image of size 4884]
sig 3        79A9CCDDB8C957F3 2023-09-26  [self-signature]
sub   rsa4096 2023-09-26 [A]
      F92E 1E75 887C 7446 3818  1A20 B1DD 0AD3 4E9E 53AD
sig          79A9CCDDB8C957F3 2023-09-26  [self-signature]
sub   rsa4096 2023-09-26 [E]
      EC03 4D6C 3F74 1766 3A0D  E830 AA09 F84D 08FB CBD7
sig          79A9CCDDB8C957F3 2023-09-26  [self-signature]
```

## 🚫 Revoked Keys 已经作废的密钥对

- These keys have been revoked, please delete and do not use them again.
- 这些密钥已经吊销，请删除并不要再使用。

### `yashipgppublickey2016lts.asc`, `yashisshpublickey2016lts.pub`

- 🔓 Revocation certificate 吊销证书:
  - [KagurazakaYashi_2016lts.rev](https://github.comkagurazakayashi/pubkey/releases/download/2023.10KagurazakaYashi_2016lts.rev)
- Fingerprint 指纹: `1F017CCB7C3BFE6CEA4F5D5D3127DF05A772B61D`
  - pub rsa4096/`501f6f8645f06a4034ccd9b63854e1ca1474714b` 2016-06-26T05:12:38Z
  - sig revok `3854e1ca1474714b` 2016-06-26T05:12:41Z
  - pub rsa4096/`1f017ccb7c3bfe6cea4f5d5d3127df05a772b61d` 2016-09-11T16:51:51Z
  - sig revok `3127df05a772b61d` 2023-09-26T06:14:52Z
