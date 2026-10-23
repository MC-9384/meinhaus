# Haus-Manager

PWA zur Verwaltung des Hauses (Baujahr 1964). Reines HTML/JS, offlinefähig, Daten in `localStorage` (Schlüssel `haus-manager`).

## Tabs

- **Kalender** – Jahreskalender mit wiederkehrenden Aufgaben (Monate wählbar, optional nur ein bestimmtes Jahr). Monatsraster mit Erledigt-Zähler, Abhaken je Jahr und Monat, „Überfällig“ ab dem Startmonat. Startbestand: Haus-/Technik-/Verwaltungsaufgaben plus Garten aus dem Second-Brain-Plan „Schnitt- und Pflegeplan Garten“.
- **Wo ist was** – freie Suche über Name, Raum, Standort, Kategorie und Details; Filter nach Raum und „Standort fehlt“; Foto und Freitext (z. B. Sicherungsbelegung). Vorlage mit 18 typischen Einträgen (Sicherungskasten, Absperrhähne, Zähler …).
- **Lager** – Werkzeug, Ersatzteile und Material mit Lagerort, Menge (+/− direkt in der Liste), Mindestbestand („Nachkaufen“), Verleih-Vermerk, Foto und Suche.
- **Verbrauch** – Zähler (Gas, Strom, Wasser vorangelegt; weitere möglich) mit Zählerständen, Differenz je Ablesung, Verbrauch pro Tag je Periode (Diagramm), Jahresverbrauch (anteilig aus den Ablesungen), Hochrechnung auf 12 Monate und optional Kosten über Preis pro Einheit.
- **Backup** – JSON-Backup/-Import und Markdown-Export fürs Second Brain.

## Entwicklung

Dev-Server: `launch.json`-Eintrag `haus-manager` (Port 8651). Änderungen an `index.html` → `CACHE` in `sw.js` hochzählen.
