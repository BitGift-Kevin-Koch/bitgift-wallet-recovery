# BitGift Wallet-Wiederherstellung (Offline)

Dieses Repository enthält ein **reines Offline-Tool zur Wiederherstellung von Bitcoin-Wallets**, 
die mit **BitGift-Karten** erstellt wurden.

Das Tool dient als **Notfall-Backup**, falls die offizielle BitGift-Webseite nicht mehr erreichbar sein sollte.

---

## 🔐 Sicherheit & Datenschutz

- ❌ Kein Server
- ❌ Kein Tracking
- ❌ Keine externen APIs
- ✅ 100 % clientseitig (HTML + JavaScript)
- ✅ Open Source & überprüfbar

Der komplette Code läuft **ausschließlich im Browser** des Nutzers.

---

## 🧰 Funktionsweise (technisch)

Die Wallet wird deterministisch aus folgenden Daten erzeugt:

seed = SHA256("BitGift-v1|" + Kartennummer + "|" + Passwort)

Verwendeter Ableitungspfad:

m/84'/0'/0'/0/0 (P2WPKH / bech32)


---

## 🌍 Online-Version (GitHub Pages)

Die Backup-Version ist hier erreichbar:

➡️ **https://bitgift-kevin-koch.github.io/bitgift-wallet-recovery**

---

## 📴 Offline-Nutzung

Das Tool kann vollständig **offline** genutzt werden:

1. Dieses Repository herunterladen (ZIP)
2. Alle Dateien in einen Ordner entpacken
3. `index.html` lokal im Browser öffnen

⚠️ **Empfehlung:** Private Schlüssel nur auf einem sicheren, sauberen Gerät anzeigen.

---

## ⚠️ Haftungsausschluss

Dieses Tool wird **ohne Gewähr** bereitgestellt.

- Der Nutzer ist selbst für die sichere Aufbewahrung seiner Zugangsdaten verantwortlich
- Es erfolgt keine Haftung für verlorene oder kompromittierte Wallets
- Nutzung auf eigene Verantwortung

---

## 📄 Lizenz

Dieses Projekt steht unter der **MIT License**.

Der Code darf geprüft, kopiert, verändert und selbst gehostet werden.
