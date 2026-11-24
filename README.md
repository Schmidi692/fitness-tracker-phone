# Fitness-Tracker · Handy-App (nur Erfassen im Studio)

Offline-fähige Web-App (PWA). Läuft nach dem ersten Laden ohne Netz.
Tabs: Heute, Verlauf, Tests, Mehr. Auswertung und Verwaltung sind in der PC-Anwendung (`../server`).

- Daten liegen nur im Browserspeicher des Handys (IndexedDB). Regelmäßig unter „Mehr“ → „Sicherung exportieren“.
- Die Sicherung am PC unter „Daten & Sicherung“ importieren. Zusammenführen je Datensatz, neuere Änderung gewinnt.
- Hosting: nur diese Dateien (ohne Daten) auf GitHub Pages, siehe Anleitung im Chat.
- Lokal testen: `python -m http.server 8765` in diesem Ordner, dann http://localhost:8765/
- Nach Änderungen an Dateien in `sw.js` die Zeile `VERSION` erhöhen, sonst bleibt die alte Version im Cache.
