# Datenschutzerklärung – Balance CRM

Stand: 10. November 2026

## Kurz gesagt

Balance CRM speichert alle Daten **ausschließlich auf deinen eigenen Geräten**, verschlüsselt. Es gibt keinen Server von uns, kein Benutzerkonto, kein Tracking, keine Werbung und keine Analyse-Werkzeuge. Wir als Anbieter haben **keinen Zugriff** auf die Kontakte, Notizen oder sonstigen Daten, die du in der App erfasst.

## Anbieter

360 Creations LLP
Richmond, British Columbia, Kanada
Marke: Findediebalance
Kontakt: apps@360creations.de

## Welche Daten die App verarbeitet

**Deine Eingaben** (Kontakte, Notizen, Aufgaben, Termine, Einwilligungen und Ähnliches) liegen in einer mit deinem Passwort verschlüsselten Datenbank auf deinem Gerät (SQLCipher, AES-256). Ohne dein Passwort kann niemand sie lesen, auch wir nicht.

**Für die Daten deiner Kundinnen und Kunden bist du selbst verantwortlich** (Verantwortliche:r im Sinne der DSGVO). Die App unterstützt dich dabei, zum Beispiel mit Feldern für Einwilligungen und Hinweisen zu Gesundheitsangaben (Art. 9 DSGVO). Wir sind für diese Daten weder Verantwortliche noch Auftragsverarbeiter, weil sie unsere Systeme nie erreichen.

**Entsperren mit Face ID, Touch ID oder Windows Hello:** Die biometrische Prüfung übernimmt das Betriebssystem. Die App erhält nur „erfolgreich“ oder „nicht erfolgreich“, niemals biometrische Daten. Das Datenbank-Passwort liegt dafür im Schlüsselbund bzw. Anmeldeinformationsspeicher des Geräts.

**Mitteilungen** (Erinnerungen an Termine, Geburtstage, LRP) werden lokal auf dem Gerät erzeugt und eingeplant. Auf Wunsch blendet die App Namen in Mitteilungen aus.

**Backups und Exporte** werden nur dort gespeichert, wo du sie hinlegst (auf dem iPad im App-Ordner der Dateien-App). Der CSV-Export ist unverschlüsselt; die App weist darauf hin.

## Verbindungen ins Netzwerk

Die App baut nur diese Verbindungen auf:

1. **Abgleich zwischen deinen Geräten (Synchronisation):** direkt im lokalen Netzwerk oder über eine von dir eingetragene Adresse, Ende-zu-Ende-verschlüsselt (ChaCha20-Poly1305) mit eurem Gruppencode. Zum Auffinden der Geräte im Heimnetz wird Bonjour/mDNS genutzt. Es läuft kein Server dazwischen.
2. **Update-Prüfung:** Die App ruft eine kleine Versionsdatei von GitHub ab (raw.githubusercontent.com). Dabei werden keine Daten aus der App übertragen. GitHub erhält technisch bedingt deine IP-Adresse (Anbieter: GitHub, Inc., USA; Datenschutz: https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
3. **Team-Kanal:** Wenn du einen Team-Kanal abonniert hast, lädt die App die Kanal-Datei von GitHub und den öffentlichen Teamkalender von Google Kalender (calendar.google.com). Es werden keine Daten aus der App übertragen; die Anbieter erhalten deine IP-Adresse (Google: https://policies.google.com/privacy).
4. **Kanal veröffentlichen (nur Teamleitungen):** Wer einen eigenen Kanal veröffentlicht, sendet die Kanal-Datei (Termine-Link, Hinweis, Ressourcen-Links, keine Kontaktdaten) mit dem eigenen GitHub-Zugangsschlüssel an das eigene GitHub-Repository.
5. **Links und Nachrichten:** Tippst du auf WhatsApp, Telegram, Telefon, SMS, E-Mail oder einen Link, öffnet die App das jeweilige Programm bzw. den Browser. Was dort passiert, richtet sich nach dem jeweiligen Anbieter.

## Keine Weitergabe, kein Tracking

Wir erheben keine Nutzungsstatistiken, setzen keine Cookies oder Werbe-IDs ein und geben keine Daten an Dritte weiter.

## Deine Rechte

Da wir keine personenbezogenen Daten von dir speichern, können wir dazu auch keine Auskunft geben oder Daten löschen. Du löschst alle Daten, indem du die App vom Gerät entfernst (inklusive eventuell angelegter Backups). Bei Fragen erreichst du uns unter der oben genannten Adresse.

## Änderungen

Ändert sich etwas an der Datenverarbeitung (zum Beispiel durch neue Funktionen), passen wir diese Erklärung an. Das Datum oben zeigt den aktuellen Stand.

---

### Privacy Policy (English summary)

Balance CRM stores all data locally on the user's own devices in an encrypted database. There is no server, no account, no tracking, no advertising and no analytics; the developer (360 Creations LLP, Richmond BC, Canada) has no access to any data entered in the app. Network connections are limited to: encrypted peer-to-peer sync between the user's own devices (local network, Bonjour/mDNS discovery), a version check against GitHub, optional download of a public team channel file (GitHub) and team calendar (Google Calendar), and links the user opens in other apps. No personal data is collected or shared. Contact: apps@360creations.de
