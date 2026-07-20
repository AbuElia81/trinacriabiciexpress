# Trinacria Bici Express

Website für geführte Radwochen in Sizilien — mit Giacomo (Noto) und Michael (Österreicher in Noto).

Statische Seite, eine Datei, kein Build-Prozess. Einfach `index.html` im Browser öffnen.

## Inhalt

- **Route A — Balsamo-Route:** Catania → Catenanuova → Agira → Leonforte → Alimena → Caltavuturo → Cerda → Termini Imerese → Trabia → Palermo. Folgt den Etappen aus dem *Giornale del viaggio fatto in Sicilia* des Abts Paolo Balsamo von 1808.
- **Route B — Val di Noto:** Noto, Marzamemi, Siracusa, Palazzolo Acreide, Ragusa, Modica, Scicli.
- Interaktive Sizilien-Karte, Etappenliste, Preis, Guides, Buchungsformular.

## Struktur

```
index.html          komplette Seite (HTML, CSS, JS in einer Datei)
fotos/
  guides-meer.jpg   Giacomo und Michael am Meer
  guides-mauer.jpg  Giacomo und Michael in Radtrikots
```

Weitere Fotos ergänzen: Datei in `fotos/` legen, Dateiname muss zum
`data-foto`-Attribut im HTML passen. Erwartet werden:
`noto.jpg`, `ortigia.jpg`, `modica.jpg`, `tisch.jpg`, `madonie.jpg`.
Fehlende Bilder zeigen automatisch einen beschrifteten Platzhalter.

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
