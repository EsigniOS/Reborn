<p align="center">
  <a href="https://esignreborn.com">
    <img src="https://esignreborn.com/assets/icon.png" alt="ESign Reborn" width="120" height="120">
  </a>
</p>

<h1 align="center">ESign Reborn</h1>

<p align="center">
  <b>The on-device IPA signer for iPhone and iPad.</b><br>
  Sign, customize, and install IPA files: no computer, no jailbreak.
</p>

<p align="center">
  <a href="https://github.com/EsigniOS/Reborn/releases/latest"><img src="https://img.shields.io/github/v/release/EsigniOS/Reborn?label=latest&color=1C7CF0" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/iOS-15.0%2B-black?logo=apple" alt="iOS 15+">
  <img src="https://img.shields.io/badge/license-AGPL--3.0-blue" alt="License: AGPL-3.0">
  <a href="https://t.me/P12Certificate"><img src="https://img.shields.io/badge/Telegram-channel-26A5E4?logo=telegram" alt="Telegram"></a>
  <a href="https://x.com/EsignPatch"><img src="https://img.shields.io/badge/X-@EsignPatch-black?logo=x" alt="X"></a>
</p>

<p align="center">
  <a href="https://esignreborn.com"><b>Website</b></a> ·
  <a href="https://esignreborn.com/sign/"><b>Install Online</b></a> ·
  <a href="https://github.com/EsigniOS/Reborn/releases/latest"><b>Download IPA</b></a> ·
  <a href="https://esignreborn.com/faq/"><b>FAQ</b></a> ·
  <a href="https://t.me/CmxPro"><b>Support</b></a>
</p>

---

## ✨ Features

### ✍️ Signing
- Sign any IPA with your own Apple developer certificate (`.p12` + `.mobileprovision`).
- Change the app name, bundle ID, version and icon. App extensions and Watch apps follow a new bundle ID automatically.
- Works with explicit and wildcard profiles, Ad Hoc and Development.
- Batch sign, Re-sign All, per-app presets, and a "Remove mobileprovision" option that keeps the signature valid.
- Signing happens **on your device**. Your certificate never leaves your iPhone.

### 🧬 Dyld Studio *(new in 7.1)*
One place for tweaks and libraries:
- Import `.deb`, `.dylib`, `.framework` or `.zip`, rootful or rootless.
- Add your own repos, search them, and download into your library.
- **Inspector**: load commands (with hex), symbols, architectures, minimum iOS, and an encrypted-IPA warning.
- **Composer**: load order, optional (weak) tweaks, Substrate or ElleKit, inject into extensions.
- **Preflight**: checks before signing whether the app will launch, and tells you what's missing.
- Signing report, **Compare with Original**, and **Remove Libraries and Re-sign**.
- Recipes: save a tweak set and apply it to many apps at once.

### 📂 Files & library
- Built-in file manager with image thumbnails and viewer, a HEX editor, and zip/unzip.
- Open IPAs straight from Files, Safari, Telegram, AirDrop and other apps.
- Package a `Payload` or `.app` folder as an IPA.
- Handles large IPAs (several GB) without running out of memory.

### 🌐 App sources
- AltStore-style sources: add many at once, import or export your list, with clear errors when a source fails.

### ☁️ ESign Cloud
- Encrypted backups of your certificates and settings. Sign in with an email code and restore on any iPhone.
- Backups are encrypted on your device with your own password before upload.

### 🔄 Updates
- Self-update from inside the app, with SHA-256 verification of every download.
- "Move ESign Reborn to another certificate" when your certificate changes.

---

## 📲 Install

**Option 1: Install Online (easiest)**
1. Open **[esignreborn.com](https://esignreborn.com)** in **Safari** on your iPhone.
2. Tap **Install Online** and choose your certificate (`.p12` + `.mobileprovision`, or an ESign Reborn `.esigncert`).
3. Enter the password and tap **Install**, then watch your Home Screen.

**Option 2: Download the IPA**
Get the latest `.ipa` from **[Releases](https://github.com/EsigniOS/Reborn/releases/latest)** and sign it with any signer you already use.

**After installing**
- If you see *Untrusted Developer*: **Settings › General › VPN & Device Management** › tap the developer › **Trust**.
- If you're asked for Developer Mode: **Settings › Privacy & Security › Developer Mode** › On, then restart.

> 🔑 **No certificate yet?** Get one at **[esignreborn.com/certificates](https://esignreborn.com/certificates/)**. You'll need your device's UDID, which you can find at **[esignreborn.com/udid](https://esignreborn.com/udid/)**.

---

## 📋 Requirements

| | |
|---|---|
| iOS / iPadOS | 15.0 or later |
| Certificate | Apple developer certificate (`.p12`) + provisioning profile that includes your device |
| Jailbreak | Not needed |
| Computer | Not needed |

---

## 🌍 Translations

ESign Reborn is available in English, العربية, Español, Português (Brasil), Русский, Türkçe, Tiếng Việt, 简体中文, 繁體中文 and 日本語, with more on the way.

**Help translate it into your language:** **[esignreborn.com/translate](https://esignreborn.com/translate/)**. Translators are credited in the app (**Settings › Translators**) and on **[our website](https://esignreborn.com/translators/)**.

---

## 🐞 Bugs & feature requests

- Open an **[issue](https://github.com/EsigniOS/Reborn/issues)**, or message **[Telegram support](https://t.me/CmxPro)**.
- Please include your iPhone model, iOS version, ESign Reborn version, and the log from **Settings › Logs › Share**.
- ⚠️ Never post your certificate, `.p12` password or UDID publicly.

---

## 📰 Changelog

See **[Releases](https://github.com/EsigniOS/Reborn/releases)** for what's new in each version.

---

## ❓ FAQ

<details>
<summary><b>Is ESign Reborn free?</b></summary>
Yes. The app is free. You need your own Apple developer certificate to sign apps.
</details>

<details>
<summary><b>Does it need a computer or jailbreak?</b></summary>
No. Everything runs on your iPhone or iPad.
</details>

<details>
<summary><b>Is my certificate uploaded anywhere?</b></summary>
No. Signing happens on your device. Install Online uses your files once to sign ESign Reborn itself, then deletes them. ESign Cloud only stores backups encrypted with your own password.
</details>

<details>
<summary><b>Why does iOS say "could not install a profile" when I get my UDID?</b></summary>
Open the link in the <b>Safari app</b>, not inside a mail or chat app. If you see "Security Delay in Progress", that's Apple's Stolen Device Protection: wait one hour, or do it at home. See <a href="https://esignreborn.com/udid/">esignreborn.com/udid</a>.
</details>

<details>
<summary><b>Can my certificate be revoked?</b></summary>
Any certificate can be revoked by Apple. No one can guarantee it won't be. Your seller's warranty terms say what's covered.
</details>

More answers: **[esignreborn.com/faq](https://esignreborn.com/faq/)**

---

## 🔗 Links

| | |
|---|---|
| 🌐 Website | [esignreborn.com](https://esignreborn.com) |
| 📢 Telegram channel | [@P12Certificate](https://t.me/P12Certificate) |
| 💬 Telegram support | [@CmxPro](https://t.me/CmxPro) |
| 𝕏 X / Twitter | [@EsignPatch](https://x.com/EsignPatch) |
| ▶️ YouTube | [@EsigniOSReborn](https://youtube.com/@EsigniOSReborn) |
| ✉️ Email | support@esignreborn.com |

---

## 📜 License & credits

ESign Reborn is free software, licensed under the **[GNU Affero General Public License v3.0](LICENSE)**. Anyone who receives the app can ask for its source code under the same license.

ESign Reborn is derived from **[SideStore](https://github.com/SideStore/SideStore)**, which is a fork of **[AltStore](https://github.com/rileytestut/AltStore)** by Riley Testut (both AGPL-3.0). It also uses SideSign, minimuxer, em_proxy, ZIPFoundation, Nuke and other open-source components. The full list is in the app under **Settings › Licenses**.

> ESign Reborn is an independent project. It is not affiliated with or endorsed by Apple Inc., or by the original ESign app or its developer. "iPhone", "iPad" and "iOS" are trademarks of Apple Inc.
