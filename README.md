# 🛡️ Guide to Online Privacy

In this guide, I’ll show you different ways to improve your privacy while navigating the internet.  
**Remember: your data is precious — don’t give it away for free!**

---
## 📧 Email

You probably use Gmail or Outlook for your email, right? While these services are convenient and offer quick authentication for many platforms (especially Google services), they are also known for collecting data for commercial purposes.

Let me show you a solid alternative:  
👉 **[Proton](https://proton.me/)**

##### What’s Proton?
**Proton Mail** is a Swiss-based, end-to-end encrypted email service, operated by the non-profit Proton Foundation.

##### ✅ Pros:
- End-to-end encryption
- No data collection
- Based in privacy-friendly Switzerland

##### ❌ Cons:
- Filters and forwarding are only available to paying users
- The mobile app is not open source
- Requires proprietary app or website unless you’re a premium user

### ✨ Email Aliasing

Ever wanted to sign up on a sketchy or poorly protected website?  
**Email aliasing** can help!

##### What is Email Aliasing?
An email alias is a forwarding address that hides your real email. Anything sent to the alias is forwarded to your actual inbox.  
⚠️ Note: This doesn’t protect you if you're doing anything illegal.

📌 Try **[SimpleLogin](https://simplelogin.io/)** — it integrates seamlessly with Proton Mail!

**What’s SimpleLogin?**  
An open-source service that creates email aliases to protect your privacy and reduce spam/phishing risks.

### 🕑 Temporary Emails
Temporary email services work similarly to aliases but are active only for a short session and don’t forward messages to your inbox.

📌 Try **[TempGmail](https://www.emailnator.com/)** — works on most sites thanks to Gmail compatibility.

---
## 💻 Windows (and Linux)

Let’s face it: Windows collects a lot of data.  
Switching to **Linux** is a great option — it’s privacy-respecting, lightweight, open-source, and highly customizable.

### 🔄 Not ready to switch?
If you're staying on Windows, here’s how to minimize tracking:

#### 🚫 Disable Tracking Features:
- [Turn off Windows Recall](https://geekchamp.com/how-to-completely-disable-or-uninstall-recall-in-windows-11-24h2/)
- [Disable Telemetry](https://gist.github.com/ave9858/a2153957afb053f7d0e7ffdd6c3dcb89) (sends diagnostics and screenshots to Microsoft)

>This also boosts performance.

#### 🧹 Debloat Windows:

Use tools like:
- [Revo Uninstaller](https://www.revouninstaller.com/)
- `msconfig`
- `services.msc`

> ⚠️ These aren’t strictly privacy-related, but they boost performance and reduce bloatware.

### 🪦 Windows 10
Support is ending soon…  
[Coff coff](https://massgrave.dev/windows10_eol)  
Or, you know — **just switch to Linux!**

### 🆕 Windows 11
Follow the same steps as above to enhance your privacy.

#### 🛠️ Useful Scripts
- **[Microsoft Activation Script](https://github.com/massgravel/Microsoft-Activation-Scripts)**
- **[Edge Remover Script](https://github.com/he3als/EdgeRemover)**  
    After using it, go to `Disk/Program Files (x86)/Microsoft/EdgeUpdate`, take ownership of the folder and revoke all permissions except for your user.

---

## 📱 Android
Another tricky one. Start by turning off all telemetry: go to your settings and search for data-sharing options.

### 🧼 Debloat
Phones come with tons of unnecessary (often hidden) apps.  
Use **[ADB](https://github.com/0x192/universal-android-debloater?tab=readme-ov-file#how-to-use-it)** and the **[Universal Android Debloater](https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation/)**.

⚠️ Be sure to use a **debloat list** to avoid removing critical apps!

### 🏅 Honorable Mention
If you own a **Google Pixel**, you can install a full **[open-source OS](https://youtu.be/u_Lxkt50xOg?t=306)**.

---

## 🔐 Password Managers & Authenticators

### Password Management
Want better security without memorizing complex passwords?  
	Use a password manager like **[Bitwarden](https://bitwarden.com/)**!

##### What’s Bitwarden?
A freemium, open-source password manager that stores your credentials in an encrypted vault.  
It helps you:
- Generate secure passwords
- Auto-fill login forms
- Sync across devices  
    ✅ It also supports **passkeys**!

### 🔒 Two-Factor Authentication (2FA)
Add an extra layer of security to your accounts with an **authenticator app**.

📌 Try **[Ente Auth](https://ente.io/auth/)** — an encrypted, open-source OTP manager.

---
## 🌐 Browsers & Search Engines
Avoid Chrome and Edge — they track you!  
Switch to **Firefox** or **Librewolf** for better privacy.

##### 🔧 Browser Settings
- Enable HTTPS-only mode
- Set "Maximum Protection"
- Use DNS like Cloudflare’s (1.1.1.1)
- Disable telemetry for more privacy if you care
- Install privacy extensions like:
    - [uBlock Origin](https://ublockorigin.com)
    - [Privacy Badger](https://privacybadger.org)
    - [LocalCDN](https://codeberg.org/nobody/LocalCDN)

Browse more tools here: [Browser Tools](https://fmhy.net/internet-tools#browser-tools)

### 🔎 Search Engines
Most engines track you — check out this [comparison table](https://searchengine.party/) to pick the most private option for your needs.

---

## 🧲 Torrenting & VPNs
When torrenting, your IP is visible to others — this can be risky.

##### 🧰 What to do:
1. Use an open-source torrent client like **[qBittorrent](https://www.qbittorrent.org/)**
2. Use a **No-Log VPN** (i.e., one that doesn’t store your activity)

Use this [VPN comparison](https://techlore.tech/vpn/) to find a trustworthy service.

> 🚨 If it’s free, it’s probably selling your data.

3. Bind your torrent client and browser to the VPN
4. Enable the **kill switch** to prevent IP leaks

---

## 📘 Glossary

|Term|Definition|
|---|---|
|**End-to-End Encryption**|Data is encrypted on your device and can only be decrypted by the intended recipient. Even the service provider can’t read it.|
|**Email Alias**|A fake email address that forwards to your real one, keeping your identity hidden.|
|**Telemetry**|Automatic data collection about your system/app usage sent back to developers.|
|**Debloat**|The act of removing unnecessary or pre-installed software from a system.|
|**ADB**|Android Debug Bridge — a command-line tool for communicating with Android devices.|
|**OTP**|One-Time Password — used for 2FA to add an extra layer of security.|
|**Passkey**|A passwordless authentication method that uses cryptographic keys.|
|**No-Log VPN**|A VPN that does not store logs of user activity or connection metadata.|
|**Kill Switch**|A VPN feature that cuts off your internet if the VPN disconnects, preventing IP leaks.|

---
## 📚 Sources

Main source: **[FMHY](https://fmhy.net)** — a reliable, community-maintained forum for privacy-respecting and open-source tools.  
Highly recommended for any future questions or tools you need!
