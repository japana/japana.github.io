---
layout: default
title: BariaTrack - Datenschutz
description: Datenschutzerklärung für BariaTrack
---

<link rel="stylesheet" href="assets/css/bariatrack-theme.css">

# Datenschutz

Deine Gesundheitsdaten sind sensibel – und wir nehmen den Schutz dieser Daten ernst.

[← Zurück zur Übersicht](index)

---

## Unsere Grundprinzipien

### 1. Deine Daten gehören dir

Alle Tracking-Daten werden **lokal auf deinem Gerät** gespeichert. Wir haben keinen Zugriff darauf.

### 2. Keine Werbung, keine Datenverkäufe

Wir verdienen Geld durch die Pro-Version – **nicht durch deine Daten**. Deine Gesundheitsdaten werden niemals an Werbetreibende oder Dritte verkauft.

### 3. Verschlüsselung wo nötig

Cloud-Backups werden mit **AES-256** verschlüsselt. Selbst wir können deine Backup-Daten nicht lesen.

### 4. Transparenz

Wir sagen dir genau, welche Daten erfasst werden und warum.

---

## Welche Daten werden erfasst?

### Lokal auf deinem Gerät

Diese Daten werden nur auf deinem Gerät gespeichert:

| Datentyp | Beschreibung |
|----------|--------------|
| Ernährungsdaten | Mahlzeiten, Nährwerte, Zeiten |
| Flüssigkeitsdaten | Getränke, Mengen, Zeiten |
| Gewichtsdaten | Gewichtswerte, Datum |
| Vitamindaten | Supplemente, Einnahmezeiten |
| Aktivitätsdaten | Schritte, Sporteinheiten |
| Stimmungsdaten | Stimmungseinträge, Notizen |
| Einstellungen | Therapieprofil, Ziele, Präferenzen |

**Diese Daten verlassen dein Gerät nur, wenn du:**
- Ein Cloud-Backup erstellst (Pro)
- Daten über Health Connect teilst (optional)
- Einen Export erstellst (Pro)

### Optional: Cloud-Backup (Pro)

Wenn du ein Cloud-Backup einrichtest:
- Du wählst den Speicherort (Google Drive, Dropbox, etc.)
- Alle Daten werden **vor dem Upload verschlüsselt**
- Dein Passwort verlässt niemals dein Gerät
- Wir können das Backup nicht entschlüsseln

### Optional: Health Connect

Wenn du Health Connect aktivierst:
- BariaTrack kann Daten lesen (Schritte, Gewicht, etc.)
- BariaTrack kann Daten schreiben (Ernährung, Gewicht, etc.)
- Die Synchronisation ist bidirektional
- Du kontrollierst, welche Daten geteilt werden

### Anonyme Nutzungsstatistiken

Wir erfassen **anonyme** Statistiken, um die App zu verbessern:
- Welche Funktionen werden genutzt?
- Welche Android-Versionen sind verbreitet?
- Absturzberichte (ohne persönliche Daten)

**Diese Daten enthalten keine persönlichen Informationen** und können nicht auf dich zurückgeführt werden.

Du kannst diese Statistiken in den Einstellungen deaktivieren.

---

## Datensicherheit

### Lokale Datenspeicherung

- Daten werden in einer **verschlüsselten Datenbank** gespeichert
- Zugriff nur über die BariaTrack-App
- Bei Geräteverlust sind die Daten geschützt

### Cloud-Backup Verschlüsselung

| Aspekt | Details |
|--------|---------|
| Algorithmus | AES-256-GCM |
| Schlüsselableitung | PBKDF2 mit SHA-256 |
| Iterationen | 600.000 (OWASP 2024 Standard) |
| Salt | 32 Bytes, zufällig pro Backup |

Kurz: **Deine Daten sind sicher verschlüsselt.**

### Passwort-Speicherung

- Dein Backup-Passwort wird **niemals im Klartext** gespeichert
- Der Schlüssel wird im **Android Keystore** gespeichert
- Der Keystore nutzt Hardware-Sicherheit (wenn verfügbar)

---

## Deine Rechte

Du hast jederzeit das Recht:

### Auskunft
Du kannst alle deine Daten in der App einsehen.

### Export
Mit BariaTrack Pro kannst du alle Daten als CSV oder PDF exportieren.

### Löschung
Du kannst deine Daten jederzeit löschen:
- Einzelne Einträge in der App löschen
- Alle Daten in den Einstellungen löschen
- App deinstallieren (löscht alle lokalen Daten)

### Widerspruch
Du kannst der anonymen Statistikerfassung in den Einstellungen widersprechen.

---

## Drittanbieter-Dienste

### Google Play Store

Für App-Download und In-App-Käufe. Googles Datenschutzrichtlinien gelten.

### Firebase Analytics (optional)

Für anonyme Nutzungsstatistiken. Kann deaktiviert werden.

### Firebase Crashlytics (optional)

Für Absturzberichte. Kann deaktiviert werden.

### Health Connect (optional)

Für Datensynchronisation mit anderen Apps. Du kontrollierst die Berechtigungen.

### Cloud-Speicher (optional)

Für Backups nutzt du deinen eigenen Cloud-Speicher (Google Drive, Dropbox, etc.). Die jeweiligen Datenschutzrichtlinien der Anbieter gelten.

---

## Kontakt

Bei Fragen zum Datenschutz:

*[Platzhalter: Kontakt-E-Mail für Datenschutzanfragen]*

---

## Änderungen

Diese Datenschutzerklärung kann aktualisiert werden. Wesentliche Änderungen werden in der App kommuniziert.

**Stand:** *[Platzhalter: Datum der letzten Aktualisierung]*

---

## Zusammenfassung

| Frage | Antwort |
|-------|---------|
| Wo sind meine Daten? | Lokal auf deinem Gerät |
| Werden Daten verkauft? | Nein, niemals |
| Ist das Backup sicher? | Ja, AES-256 verschlüsselt |
| Kann ich Daten löschen? | Ja, jederzeit |
| Gibt es Werbung? | Nein |

---

[← Zurück zur Übersicht](index) | [Support →](support)
