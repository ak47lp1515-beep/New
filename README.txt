AGA-SCHLAFTRAINER – iPhone PWA

INHALT
- index.html: App mit Schlaftracker, AGA-Countdown, Checkliste, Erinnerungszeiten und Verlauf
- manifest.webmanifest + sw.js: Installations-/Offline-Dateien
- icon-192.png / icon-512.png: App-Symbole
- AGA-Schlaftrainer-Erinnerungen.ics: wird in der App per Button erstellt; wiederkehrende Kalender-Erinnerungen bis zum 01.01.2027

WICHTIG
Für „Zum Home-Bildschirm“ muss die App über eine HTTPS-Adresse geöffnet werden. Nur die HTML-Datei lokal in Safari zu öffnen reicht nicht für eine vollständige PWA-Installation.

EINFACHE HOSTING-OPTION (GitHub Pages)
1. Auf github.com anmelden oder Konto erstellen.
2. Neues öffentliches Repository erstellen, z. B. aga-schlaftrainer.
3. Alle Dateien aus diesem Ordner hochladen (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png).
4. Im Repository Settings > Pages öffnen.
5. Bei Build and deployment „Deploy from a branch“ wählen, Branch „main“, Ordner „/ (root)“, speichern.
6. Warten, bis GitHub die HTTPS-Webadresse anzeigt. Diese Adresse auf dem iPhone in Safari öffnen.
7. Safari: Teilen-Symbol > „Zum Home-Bildschirm“ > „Als Web-App öffnen“ falls angezeigt > Hinzufügen.
8. Das neue AGA-Schlaftrainer-Symbol auf dem Home-Bildschirm starten.

NUTZUNG
- Schlaftracker: Schlaf-/Aufstehzeit und Qualität speichern.
- Checkliste: Tageshäkchen bleiben lokal auf dem iPhone und setzen sich pro Tag zurück.
- Erinnerungen: Zeiten einstellen und speichern.
- Kalenderdatei: In der App „Kalender-Erinnerungen herunterladen“ drücken. Die heruntergeladene .ics-Datei in Dateien öffnen und zum Kalender hinzufügen. Prüfe, ob die drei täglichen Termine samt Alarm importiert wurden.
- Daten exportieren: Erstellt eine JSON-Sicherung der Schlafdaten.

DATENSCHUTZ / GRENZEN
Die Schlafdaten werden in localStorage auf dem Gerät gespeichert und nicht an einen Server gesendet. Browserdaten löschen oder die App-Daten entfernen kann die Einträge löschen; nutze den Datenexport als Sicherung.
Die App hat keinen Push-Server. Web-Mitteilungen sind keine zuverlässigen Hintergrundalarme, wenn die App geschlossen ist. Für zuverlässige Hinweise bitte Kalenderdatei importieren oder Erinnerungen in Apples Erinnerungen-App einrichten.
