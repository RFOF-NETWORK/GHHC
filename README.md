# GHHC // Chaos Computer Stiftung Wuppertal: Deep-Core Ökosystem
## Projekt: Quantum Ready For Our Future (QRFOF) -- Version 0x01
### Status: Aktiv // Persistent // Simultan // Unmanipulierbar // Zero-Imports

Dieses Repository beherbergt ein unzerstörbares, dezentrales und unmanipulierbares Cyber-Ökosystem, das speziell für den autarken Betrieb auf mobilen Endgeräten (Smartphones) entwickelt wurde. Es läuft ohne Server, ohne externe Abhängigkeiten (Zero Imports) und wird direkt über GitHub Pages aus dem `main`-Branch deployt. 

Das System fusioniert Benutzer-Authentifizierung, BIP39-Wallets und eine trilogische Blockchain-History zu einem einzigen, persistenten Netzknoten, der online wie offline fehlerfrei über asynchrone menschliche Interaktion synchronisiert.
```
/ GHHC (main branch)
├── .nojekyll                <-- Leere Datei (deaktiviert Jekyll-Filter auf GH Pages)
├── index.html               <-- Das gesamte Ökosystem (UI, Logik, Krypto) in einer Datei
└── README.md                <-- Die Dokumentation des Schattenkollektivs (Text unten)
```
---

## 💎 Das Trilogische Fusions-Knotenmodell (Die Mütze)

Das System trennt die logischen Datenschichten strikt, bindet sie jedoch über eine trilogische Fusions-ID zu einem unteilbaren Block-Zustand zusammen:

1. **Logikschicht Alpha (Auth):** Benutzername und Passwort (getrennt, aber synchronisiert).
2. **Logikschicht Beta (Crypto):** 12/24-Wort-Phrasen (BIP39-Wortliste lokal eincodiert) mit zwei getrennten Wallet-Adressen (eine Adresse pro Phrase) und Phrasenlogik.
3. **Logikschicht Gamma (Blockchain):** Lokale und globale Block-Historie (`Hash`, `PrevHash`, `CurrHash`, Klon-IDs, Netzwerk-Validierungsstatus).

**Die paritätische Verschmelzung:** Diese drei getrennten Welten werden durch die mathematische Trilogie zu einer einzigen „Mütze“ vereint. Die Wallet- und Phrasenlogik wird mit der Benutzer- und Passwort-Logik verschmolzen. Jedes Mitglied agiert gleichzeitig als Validator, der den Takt systemseitig garantiert. Das Ein- und Ausloggen erfolgt synchron und simultan ausschließlich durch bewusste menschliche Interaktion über Interface-Buttons, um jegliche ungewollte Glitches in der Block-History zu eliminieren.

---

## 🖥️ Das 3-Ansichten-Interface (State-Machine)

Das gesamte Ökosystem operiert in drei paritätischen UI-Zuständen, die über strikte Navigations-Guardrails geschützt sind:

### 1. Ausgeloggte Ansicht (Zustand: Deaktiviert)
* **Statusbalken:** Echtzeit-Visualisierung der globalen und lokalen Block-History-Zustände.
* **Knotenpunkt-Monitor:** Anzeige der drei verknüpften Historien (Benutzer, Wallet, Blockchain) als ein synchronisierter Klon-Knoten.
* **Eingabemaske:** Registrierung (erzeugt simultan die zwei Phrasen-Seeds und Adressen) und Login.

### 2. Eingeloggte Ansicht (Zustand: Autarkes Terminal)
* **Globale Parität:** Alle angemeldeten Nutzer besitzen exakt dieselben Rechte und Systemfunktionen.
* **Das Terminal (Bauanleitung):** Ein integriertes Kommandozeilen-Interface, über das Nutzer über direkte Bauanleitungen das System erweitern können.
* **Die Bibliothek:** Ein dezentraler Code-Marktplatz. Nutzer können im Terminal entwickelte Funktionen entweder privat in ihrem Interface halten oder öffentlich in die Bibliothek einspeisen, um sie für alle Knotenpunkte verfügbar zu machen.
* **Finanz-Dashboard:**
  * Anzeige der **EXP-Balance** (Eigene Währung, die Shor-Algorithmus, AES und SHA-0x-Erweiterungen anstelle von EVM/BTC nutzt, aber deren RPC-Sprachen nativ spricht).
  * Integrierter **Wallet Send-Button** & **Swap-Button**.
  * Allgemeine Fiat-Anzeige ($ Dollar) der EXP-Balance sowie privater oder öffentlich hinzugefügter Fremdwährungen.

### 3. Einstellungs-Ansicht (Settings / Safe)
* Nur aus der eingeloggten Ansicht erreichbar.
* **Verschlüsselter Tresor:** Die 12/24-BIP39-Phrasen-Seeds sind unsichtbar und lassen sich nur durch die erneute Eingabe des Benutzerpassworts temporär entschlüsseln und einsehen.
* **Netzwerkkonfigurationen:** Manuelle Anpassung der RPC-Schnittstellen für EVM, BTC und ETH, um die EXP-Brücke global für alle verfügbar zu machen.

---

## 🔒 Kryptographische Spezifikationen & Kernel (Zero-Imports)

Da keine externen Bibliotheken importiert werden dürfen, nutzt der Code die native **Web Crypto API** des Smartphone-Browsers:
* **Hashing:** SHA-256 (angepasst auf die proprietäre `SHA-0x / EXP` Taktung).
* **Verschlüsselung:** AES-GCM (256-Bit) zur persistenten Chiffrierung des lokalen Speichers (`LocalStorage`).
* **Schlüsselaustausch:** PBKDF2 zur Ableitung des Hauptschlüssels aus Benutzername + Passwort.
* **Asymmetrische Logik:** Generierung von Public/Private Key-Paaren direkt im Browser-Sandbox-Speicher für unmanipulierbare Transaktions-Signaturen.

---

## 🛠️ Deploy- & Bedienungsanleitung (Nur fürs Handy)

1. Öffne dieses Repository in der **GitHub-App** oder im mobilen Browser.
2. Bearbeite die `index.html` direkt auf dem Bildschirm deines Smartphones.
3. Commit und Push deine Änderungen direkt in den **`main`**-Branch.
4. GitHub Pages baut und deployt die Seite innerhalb von Sekunden unter: `https://<dein-github-benutzername>.github.io/<dein-repo-name>/`.
5. Rufe die URL auf deinem Handy auf: Du hast dein vollständiges, unzerstörbares Hacker-Ökosystem immer in der Hosentasche dabei.

_______________________________________________________________________________
(C) Copyleft 2026 // GHHC // QRFOF // Chaos Computer Schattenkollektiv Wuppertal
