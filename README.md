# Matheapps

Kleine Web-Apps für den Mathematikunterricht in der Grundschule (NRW, Klasse 1–4).
Jede App ist eine eigenständige HTML-Seite ohne Build-Schritt und ohne Server.
Gedacht für iPad, Handy und Digiboard (iPad gespiegelt).

| Ordner | App | Inhalt |
|---|---|---|
| `blitzrechnen/` | Blitzrechnen | Zehner-/Zwanzigerfeld kurz zeigen, Würfel, Vorlesefunktion |
| `schuettelbox/` | Schüttelbox und Zahlenhaus | Zahlzerlegung mit Schüttelbox, Wendeplättchen oder Würfeln, Zahlenhaus, Partnermodus |

Startseite: `index.html` im Hauptordner – dort wählt man die App. Jede App lässt sich auch direkt über `index.html` im jeweiligen Ordner öffnen.

Gemeinsam für alle Apps im Hauptordner: `impressum.html`, `datenschutz.html`, `recht.css`, `icon.svg`, `apple-touch-icon.png` und die Schrift Andika in `fonts/` (SIL Open Font License, lokal ausgeliefert, kein Google-Server). Die Schüttelbox hat eine eigene Kopie der Schrift in `schuettelbox/fonts/`.

Neue App hinzufügen: Ordner mit `index.html` und `icon.svg` anlegen, in der Fußzeile auf `../`, `../impressum.html` und `../datenschutz.html` verlinken, eine Karte in die Startseite eintragen und die Datenschutzerklärung ergänzen, falls die App etwas Neues speichert oder nutzt (z. B. Mikrofon).
