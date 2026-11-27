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

## Einstellungen per Link

In beiden Apps gibt es in den Einstellungen „Link kopieren“. Ein solcher Link öffnet die App genau so eingestellt – praktisch, um Kindern oder Gruppen einen fertigen Link zu geben. Link-Einstellungen gelten nur für diese Sitzung und werden auf dem Gerät nicht gespeichert. Namen und Lehrkraft-Code kommen nie in den Link.

- **Blitzrechnen** (`blitzrechnen/?…`): `spiel` (blitz, dazuweg, vergleichen, rueckwaerts, wuerfel), `feld` (10, 20), `anordnung` (links, oben, untereinander), `bild` (fuchs, eule, mix, punkte, punkte5), `fragen` (wieviele, frei, obenunten, mehr, bis, nachbarn, doppelt, haelfte, wie – mit Komma), `fragemodus` (alle, eine), `richtung` (dazu, weg, beides), `schritt` (1–3), `neu` (farbe, rahmen, beides), `blitz` (1, 2, 3, 5, lehrkraft), `wuerfel` (1–3), `reihen` (1, 2), `farbe`/`farbe2` (rot, blau, gruen, gelb, weiss), `summe` (10, 20, alle), `vorlesen` (aus, fragen, alle), `tempo` (langsam, normal), `zahlen` (z. B. `5-8,12`).
  Beispiel: `blitzrechnen/?spiel=blitz&feld=20&blitz=2&fragen=wieviele`
- **Schüttelbox** (`schuettelbox/?…`): `zahl` (oder `n`), `zr` (10, 20, 100), `ansicht` (beide, box, haus), `null` (1 = mit 0, 0 = ohne 0), `material` (oder `mat`: box, plaettchen, wuerfel), `kammern` (offen, links, rechts, beide, zufall), `eintragen` (auto, kinder), `plus` (knopf, immer, aus), `wuerfel` (dach, kammer), `kugeln` (echt, gleich), an/aus mit 1/0: `boxzahl`, `ordnen`, `leer`, `muster`, `anzahl`, `linien`, `ton`, `vorlesen`, `partner`, `kinder` (Kinder-Ansicht; beenden über „🔒 Lehrkraft“ mit Rechenfrage).
  Beispiel: `schuettelbox/?zahl=7&ansicht=haus&null=0`
