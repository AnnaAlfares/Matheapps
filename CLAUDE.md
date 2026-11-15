# Hinweise für KI-Agenten

- Zielgruppe: Grundschulkinder (v. a. Klasse 1) und ihre Lehrerin. Sprache der Oberfläche: Deutsch, kindgerecht, kurz.
- Jede App = eine selbstständige `index.html` (HTML, CSS, JS in einer Datei). Keine Frameworks, kein Build, keine externen Skripte außer Google Fonts.
- Bedienung per Touch (iPad/Handy) und am Digiboard: große Tippflächen (mind. 44 px), keine Abhängigkeit von Tastatur.
- Farbcode Zahlzerlegung: links/erster Teil blau, rechts/zweiter Teil rot.
- Didaktik: keine Punkte/Ranglisten, kooperativ, Fehler sind Teil des Lernens. Nichts vorwegnehmen (Lösungen, Anzahlen, Sortierung erst auf Knopfdruck).
- Einstellungen in `localStorage`, Zugriffe immer in try/catch.
- Datenschutz: keine Daten an Server senden, keine Tracker. Impressum/Datenschutz siehe `blitzrechnen/`.
- Vor jeder Änderung testen: iPad-Breite (~1180 px) und Handy-Breite (~390 px).
