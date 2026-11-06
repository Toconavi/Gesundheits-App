# Wechseljahre-Tagebuch – Handy-App

## Was enthalten ist
- Eigenständige PWA, installierbar auf Android und iPhone
- Keine Claude-/ChatGPT-Anmeldung und kein kostenpflichtiger Account
- Lokale Speicherung auf dem jeweiligen Gerät
- Offline-Nutzung nach dem ersten Laden
- JSON-Sicherung herunterladen und wieder einlesen
- Beim ersten Start gibst du deinen Vornamen selbst ein; er wird nur lokal auf dem Gerät gespeichert
- Vorhandene Tagebuch-, Kalender-, Fragebogen-, Analyse- und Berichtsfunktionen bleiben enthalten

## Wichtig zur Installation
Die Dateien müssen über eine HTTPS-Adresse bereitgestellt werden. Das Öffnen von `index.html` direkt aus dem Dateimanager reicht für die Installation und Offline-Funktion nicht aus.

Eine kostenlose Möglichkeit ist GitHub Pages:
1. Ein kostenloses GitHub-Konto erstellen bzw. anmelden.
2. Ein neues öffentliches Repository anlegen (z. B. `wechseljahre-tagebuch`).
3. Den Inhalt dieses Ordners hochladen (index.html, manifest.webmanifest, sw.js und icons).
4. In den Repository-Einstellungen unter **Pages** die Veröffentlichung über den `main`-Branch und `/ (root)` aktivieren.
5. Die angezeigte HTTPS-Adresse auf dem Handy öffnen.

## Auf Android installieren
1. Die veröffentlichte HTTPS-Adresse in Chrome öffnen.
2. Menü ⋮ öffnen.
3. **App installieren** oder **Zum Startbildschirm hinzufügen** auswählen.
4. Das Symbol erscheint wie eine normale App.

## Datensicherheit / Datenschutz
Die Tagebuchdaten liegen im lokalen Speicher des Browsers auf diesem Gerät. Es gibt keinen Server und keine automatische Synchronisierung. Daher:
- Regelmässig unter **Mehr → Datensicherung → Sicherung herunterladen** eine Sicherung speichern.
- Nach Handywechsel die JSON-Sicherung in der App auf dem neuen Gerät laden.
- Browserdaten nicht löschen, bevor eine Sicherung erstellt wurde.
- Wer Zugriff auf das entsperrte Handy bzw. das Browserprofil hat, könnte möglicherweise auch auf die Tagebuchdaten zugreifen.

Die App ist ein Dokumentationswerkzeug und ersetzt keine medizinische Beratung. Therapie und Dosierung weiterhin mit der behandelnden Ärztin/dem behandelnden Arzt abstimmen.

Datenschutz: JSON-Sicherungen enthalten persönliche Gesundheitsangaben im Klartext. Bitte sicher aufbewahren und nicht öffentlich hochladen.
