# 🛡️ Guida alla Privacy Online

In questa guida ti mostrerò diversi modi per migliorare la tua privacy mentre navighi su internet.
**Ricorda: i tuoi dati sono preziosi — non regalarli gratis!**

---

## 📧 Email

Probabilmente usi Gmail o Outlook per la tua email, giusto?
Questi servizi sono comodi e offrono autenticazione rapida per molte piattaforme (soprattutto i servizi Google), ma sono anche noti per raccogliere dati a scopo commerciale.

Ecco una solida alternativa:

👉 **[Proton](https://proton.me/)**

##### Cos’è Proton?

**Proton Mail** è un servizio email svizzero con crittografia end-to-end, gestito dalla fondazione no-profit Proton Foundation.

##### ✅ Vantaggi:

* Crittografia end-to-end
* Nessuna raccolta dati
* Basato in Svizzera, un paese amico della privacy

##### ❌ Svantaggi:

* Filtri e inoltri disponibili solo per utenti a pagamento
* L’app mobile non è open source
* Richiede app o sito proprietario, a meno che non si sia utenti premium

### ✨ Alias Email

Vuoi registrarti su un sito sospetto o poco sicuro?

**L’alias email** può aiutarti!

#### Cos’è un Alias Email?

Un alias è un indirizzo di inoltro che nasconde la tua email reale.
Tutto ciò che viene inviato all’alias viene reindirizzato alla tua casella di posta effettiva.
⚠️ Nota: non ti protegge se stai facendo qualcosa di illegale.

📌 Prova **[SimpleLogin](https://simplelogin.io/)** — si integra perfettamente con Proton Mail!

**Cos’è SimpleLogin?**

Un servizio open-source che crea alias email per proteggere la tua privacy e ridurre il rischio di spam e phishing.

### 🕑 Email Temporanee

Funzionano in modo simile agli alias, ma sono attive solo per una sessione breve e non inoltrano messaggi alla tua inbox.

📌 Prova **[SmailPro](https://smailpro.com/temporary-email)** — funziona sulla maggior parte dei siti grazie alla compatibilità con Gmail.

### 💀 Sei stato pwned!

Se ricevi molte email di phishing, probabilmente sei stato compromesso.

Puoi verificarlo qui: **[HaveIBeenPwned](https://haveibeenpwned.com/)**

---

## 💻 Windows (e Linux)

Ammettiamolo: Windows raccoglie molti dati.

Passare a **Linux** è un’ottima scelta — rispetta la privacy, è leggero, open-source e altamente personalizzabile.

### 🔄 Non sei pronto a cambiare?

Se resti su Windows, ecco come ridurre il tracciamento:

#### 🚫 Disattiva le Funzioni di Tracciamento:

* [Disattiva Windows Recall](https://support.microsoft.com/en-us/windows/privacy-and-control-over-your-recall-experience-d404f672-7647-41e5-886c-a3c59680af15)
* [Disabilita Telemetria](https://gist.github.com/ave9858/a2153957afb053f7d0e7ffdd6c3dcb89) (invia diagnostica e screenshot a Microsoft)

> Questo migliora anche le prestazioni.

#### 🧹 Alleggerisci Windows (Debloat):

Usa strumenti come:

* [Revo Uninstaller](https://www.revouninstaller.com/)
* `msconfig`
* `services.msc`

> ⚠️ Non strettamente legati alla privacy, ma migliorano le prestazioni e riducono i programmi inutili.

### 🪦 Windows 10

Il supporto sta per finire…

[Coff coff](https://massgrave.dev/windows10_eol)

Oppure… **passa direttamente a Linux!**

### 🆕 Windows 11

Segui gli stessi passaggi sopra per aumentare la privacy.

#### 🛠️ Script Utili

* **[Microsoft Activation Script](https://github.com/massgravel/Microsoft-Activation-Scripts)**
* **[Edge Remover Script](https://github.com/he3als/EdgeRemover)**
  Dopo averlo usato, vai su `Disk/Program Files (x86)/Microsoft/EdgeUpdate`, prendi possesso della cartella e rimuovi tutte le autorizzazioni tranne quelle per il tuo utente.

---

## 📱 Android

Altro caso complicato.

Inizia disattivando tutta la telemetria: vai nelle impostazioni e cerca le opzioni di condivisione dati.

### 🧼 Rimuovere App Inutili (Debloat)

I telefoni vengono forniti con molte app inutili (spesso nascoste).
Usa **[ADB](https://github.com/0x192/universal-android-debloater?tab=readme-ov-file#how-to-use-it)** e **[Universal Android Debloater](https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation/)**.

⚠️ Assicurati di usare una **lista di debloat** per rimuovere app di raccolta dati e spyware segnalati, evitando di eliminare app critiche!

### 🏅 Menzione d’Onore

Se possiedi un **Google Pixel**, puoi installare un **[sistema operativo open-source](https://youtu.be/u_Lxkt50xOg?t=306)** completo.

---

## 🔐 Gestione Password & Autenticazione

### Gestione Password

Vuoi più sicurezza senza dover ricordare password complesse?

Usa un password manager come **[Bitwarden](https://bitwarden.com/)**!

#### Cos’è Bitwarden?

Un password manager open-source freemium che archivia le tue credenziali in un vault criptato.

Ti aiuta a:
* Generare password sicure
* Compilare automaticamente i form di login
* Sincronizzare su più dispositivi
  ✅ Supporta anche le **passkey**!

### 🔒 Autenticazione a Due Fattori (2FA)

Aggiungi un ulteriore livello di sicurezza con un’app autenticatrice.

📌 Prova **[Ente Auth](https://ente.io/auth/)** — un gestore OTP open-source e criptato.

---

## 🌐 Browser & Motori di Ricerca

Evita Chrome e Edge — ti tracciano!

Passa a **[Firefox](https://github.com/mozilla-firefox/firefox)** o **[Librewolf](https://librewolf.net/)** per maggiore privacy.

#### 🔧 Impostazioni del Browser
* Abilita modalità solo HTTPS
* Imposta "Protezione Massima"
* Usa DNS come Cloudflare (1.1.1.1)
* Disabilita la telemetria per più privacy
* Installa estensioni per la privacy come:
  * [uBlock Origin](https://ublockorigin.com)
  * [Privacy Badger](https://privacybadger.org)
  * [LocalCDN](https://codeberg.org/nobody/LocalCDN)

Altri strumenti qui: [Browser Tools](https://fmhy.net/internet-tools#browser-tools)

### 🔎 Motori di Ricerca

Molti motori ti tracciano — consulta questa [tabella comparativa](https://searchengine.party/) per scegliere l’opzione più privata.

---

## 🧲 Torrent & VPN

Quando usi torrent, il tuo IP è visibile agli altri — rischioso.

#### 🧰 Cosa fare:
1. Usa un client torrent open-source come **[qBittorrent](https://www.qbittorrent.org/)**
2. Usa una **VPN No-Log** (che non registra la tua attività)

Confronta qui: [VPN comparison](https://techlore.tech/vpn/)

> 🚨 Se è gratis, probabilmente vende i tuoi dati.

3. Associa client torrent e browser alla VPN
4. Attiva il **kill switch** per evitare perdite di IP

---

## 🐦 X / Twitter

Se vuoi evitare il vecchio Twitter, che richiede cookie e account per visitare i contenuti,

ti consiglio **[xcancel](https://xcancel.com/about)**!

Ti permette di accedere ai tweet e alle pagine degli utenti senza tracciamento e senza account.

---

## 📘 Glossario

| Termine                     | Definizione                                                                                                                                 |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Crittografia End-to-End** | I dati sono criptati sul tuo dispositivo e possono essere decriptati solo dal destinatario. Nemmeno il fornitore del servizio può leggerli. |
| **Alias Email**             | Un indirizzo email falso che inoltra i messaggi alla tua email reale, nascondendo la tua identità.                                          |
| **Telemetria**              | Raccolta automatica di dati sul tuo sistema/uso app, inviata agli sviluppatori.                                                             |
| **Debloat**                 | Rimozione di software inutile o preinstallato da un sistema.                                                                                |
| **ADB**                     | Android Debug Bridge — strumento a riga di comando per comunicare con dispositivi Android.                                                  |
| **OTP**                     | One-Time Password — usata per la 2FA per aggiungere un livello di sicurezza extra.                                                          |
| **Passkey**                 | Metodo di autenticazione senza password che usa chiavi crittografiche.                                                                      |
| **VPN No-Log**              | VPN che non registra dati o metadati sull’attività dell’utente.                                                                             |
| **Kill Switch**             | Funzione VPN che interrompe la connessione internet se la VPN si disconnette, prevenendo perdite di IP.                                     |

---

## 📚 Fonti

Fonte principale: **[FMHY](https://fmhy.net) / [r/FREEMEDIAHECKYEAH](https://www.reddit.com/r/FREEMEDIAHECKYEAH/)** — forum affidabile, mantenuto dalla community, per strumenti open-source e rispettosi della privacy.

Altamente consigliato per domande future o ricerca di nuovi strumenti!

Altre fonti: [r/privacy](https://www.reddit.com/r/privacy/), [r/VPN](https://www.reddit.com/r/VPN/)
