# Trinacria Bici Express

Website für geführte Radwochen in Sizilien — mit Giacomo (Noto) und Michael (Österreicher in Noto).

Statische Seite, eine Datei, kein Build-Prozess. Einfach `index.html` im Browser öffnen.

Zwei Routen auf den Spuren des Abts Paolo Balsamo (1808), beide ab Palermo,
oben im Routenabschnitt umschaltbar:

- **Route A — Ätna-Route:** Palermo → Termini Imerese → Caltavuturo → Alimena → Leonforte → Catenanuova → Catania (272 km).
- **Route B — Grafschaft Modica:** Palermo → Corleone → Agrigento → Gela → Ragusa → Modica → Scicli → Noto (299 km, nach der Komoot-Tour). Bei Route B ist ein Link zur Komoot-Strecke eingeblendet.
- Eigener Abschnitt zur Person Paolo Balsamo, mit zwei Originalzitaten aus dem Reisetagebuch.
- Sizilien-Karte mit beiden Routen und Radfahrer, Etappenliste, Preis, Guides, Buchungsformular.
- Karte, Etappenliste und Galerie wechseln mit der gewählten Route.
- Dreisprachig (Deutsch, Englisch, Italienisch), umschaltbar oben rechts.

## Struktur

```
index.html          komplette Seite (HTML, CSS, JS in einer Datei)
fotos/
  guides-meer.jpg   Giacomo und Michael am Meer
  guides-mauer.jpg  Giacomo und Michael in Radtrikots
```

Die Galerie „Die Route in Bildern" wechselt mit der gewählten Route und zieht
freie Fotos von Wikimedia Commons (Nachweise in `fotos/BILDNACHWEIS.md`):

- **Route A:** `palermo.jpg`, `termini.jpg`, `madonie.jpg`, `leonforte.jpg`, `catania.jpg`, `tisch.jpg`
- **Route B:** `agrigento.jpg`, `ragusa.jpg`, `modica.jpg`, `scicli.jpg`, `noto.jpg`, `marzamemi.jpg`

Foto ersetzen: Datei in `fotos/` mit gleichem Namen überschreiben (die Zuordnung
steht im `GALLERY`-Objekt im Skript). Fehlt eine Datei, zeigt die Kachel
automatisch einen beschrifteten Platzhalter.

## Vor dem Livegang noch erledigen

1. **Kontakt** im Footer eintragen (E-Mail, Telefon).
2. **Zahlung:** In `index.html` nach `STRIPE_PAYMENT_LINK_HIER_EINSETZEN` suchen.
   Im Stripe-Dashboard einen Zahlungslink über 300 € (Anzahlung) anlegen,
   URL einsetzen und beim Button `display:none` auf `display:block` ändern.
3. **Formular:** Das Anfrageformular zeigt bisher nur eine Bestätigung an und
   verschickt nichts. Schnellster Weg: Formspree — `<form>`-Tag um
   `action="https://formspree.io/f/DEIN-CODE" method="POST"` ergänzen und den
   `submit`-Handler im Skript entfernen.
4. **Impressum und Datenschutz** ergänzen (in Italien und Österreich Pflicht).

## Veröffentlichen mit GitHub Pages

Settings → Pages → Source: `Deploy from a branch` → Branch `main`, Ordner `/ (root)` → Save.
Die Seite ist danach unter `https://<benutzername>.github.io/trinacria-bici-express/` erreichbar.

## Bildrechte

Die Fotos in `fotos/` gehören Giacomo und Michael. Keine fremden Bilder einbinden,
ohne die Lizenz geklärt zu haben.
