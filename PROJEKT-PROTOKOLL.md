# Trinacria Bici Express — Projektprotokoll

Zusammenfassung des kompletten Arbeitsverlaufs, von der Quelle bis zur fertigen dreisprachigen Website.

---

## 1. Ausgangspunkt: die Quelle

Grundlage war ein Artikel von Antonino Messana auf **alqamah.it** (25. Februar 2017), Teil der Serie
*„La favola delle Regie Trazzere di Sicilia"*, Kapitel IV, Teil IX.

Inhalt: die letzte Etappe des *Giornale del viaggio fatto in Sicilia* des Abts **Paolo Balsamo**,
der die Insel 1808 zusammen mit dem Cavaliere Tommasi bereiste. Die Reise begann am 13. Mai
und endete am 16. Juni 1808. Die Schlussetappe führte von **Catania nach Palermo** über:

Catania → Catenanuova → San Filippo d'Agirò (Agira) → Nissoria → Leonforte → Priolo →
Alimena → Caltavuturo → Cerda → Termini Imerese → Trabia → Palermo

Balsamo, Professor für Landwirtschaftsökonomie, notierte zu jedem Ort Einwohnerzahl,
Flächen (in salme di Palermo), Straßenzustand und Viehbestand. Beispiele:

- **Catania:** 45.000 Einwohner, fünf ansehnliche Hauptstraßen, der Rest ärmlich; 1.600 Rinder, 6.000 Schafe.
- **Caltavuturo:** armes, schmutziges Dorf unter einem überhängenden Felsen; Unterkunft in einer
  „schwarzen und schmutzigen" Kammer, der giuratoria.
- **Termini Imerese:** Balsamos Geburtsstadt, über 14.000 Einwohner, Fischerei (Sardinen und
  Sardellen für den Export nach Livorno) und Getreideverladung.

Messanas These: Wenn ein so qualifizierter Zeuge 850 km zurücklegt, 38 Städte beschreibt und
dabei nie eine Viehtrift (trazzera armentizia) erwähnt, dann hat es die 11.500 km angeblicher
Regie Trazzere von rund 38 m Breite nie gegeben — außer auf kurzen Abschnitten. Er stützt sich
auf Luigi Santagati, wonach die kanonische Breite von 37,68 m nur bei Transhumanzabschnitten in
offener Landschaft erreicht wurde, sonst 3–4 m. Echte Transhumanz betraf nur wenige Bergorte
(Mistretta, Capizzi, Cesarò, Troina). Ab 1824 begann der Bau befahrbarer Straßen.

**Warum das für das Projekt zählt:** Diese Etappenfolge ist der historische Kern der Marke.
Route A fährt Balsamos Linie nach. Kein Mitbewerber hat das.

---

## 2. Das Angebot

Zwei Guides mit Sitz in Noto:

| | |
|---|---|
| **Giacomo** | Sizilianer aus Noto. Italienisch, Englisch. |
| **Michael** | Österreicher, lange in Noto ansässig. Deutsch, Italienisch, Englisch. |

Konzept: geführte Radwoche, ca. **vier Stunden Rad pro Tag**, der Rest gutes Essen,
Stadtführungen und lokale Insidertipps. Übernachtung in Pensionen, inklusive.
Zielmärkte: deutschsprachig, englischsprachig, italienisch.

### Route A — Balsamo-Route (Catania → Palermo)
272 km, 3.200 hm, 7 Tage, Niveau mittel.
Tagesetappen: Catania · Catania→Catenanuova · Catenanuova→Leonforte · Leonforte→Alimena ·
Alimena→Caltavuturo · Caltavuturo→Termini Imerese · Termini→Trabia→Palermo.

### Route B — Val di Noto
307 km, 3.600 hm, 7 Tage, Niveau mittel.
Tagesetappen: Noto · Noto→Marzamemi→Noto · Noto→Avola→Siracusa · Siracusa→Palazzolo Acreide ·
Palazzolo→Ragusa Ibla→Modica · Modica→Scicli→Sampieri→Modica · Modica→Noto.

---

## 3. Die Preisfrage

Der ursprüngliche Ansatz von **800 €** pro Person und Woche lag unter den Selbstkosten.
Kalkulation bei sieben Gästen, pro Person:

| Position | € |
|---|---|
| 6 Nächte Pension mit Frühstück (55 €/Nacht) | 330 |
| Begleitfahrzeug: Miete, Sprit, Maut (≈750 € ÷ 7) | 107 |
| Zwei Guides, 7 Tage (2 × 7 × 140 € ÷ 7) | 280 |
| Abschlussessen | 40 |
| Wasser, Snacks, Granita, Eintritte | 45 |
| Versicherung, Website, Buchungsgebühren, Ausfallrisiko | 65 |
| **Selbstkosten** | **867** |

Bei 800 € entsteht also ein Verlust — und die 280 € Guide-Honorar sind darin bereits knapp
bemessen (140 € brutto pro Kopf und Tag für rund 12 Stunden Arbeit, vor Steuern und Beiträgen).

**Festgelegter Preis: 1.290 €** pro Person.
Deckungsbeitrag ca. 420 € pro Gast, bei sieben Gästen rund 2.900 € Rohertrag pro Woche,
also je etwa 1.450 € für Giacomo und Michael, vor Steuern.
Marktvergleich: geführte Radwochen in Sizilien liegen üblicherweise bei 1.400–2.200 €.

Staffelung auf der Website:
- Einzelzimmer **+ 180 €**
- Nebensaison (März, November) **− 100 €**
- Ab vier gemeinsam Anreisenden **− 90 €** pro Person
- Anzahlung **300 €**, Rest bis vier Wochen vor Anreise

**Sparvariante** (falls doch näher an 800 € gewünscht): kein Begleitfahrzeug (−100 €),
nur ein Guide statt zwei (−140 €), mindestens acht Gäste und günstigere Pensionen in der
Nebensaison. Ergebnis: etwa 950–990 €. Darunter arbeitet ihr unter Mindestlohn.

---

## 4. Die Website

Eine einzige Datei, `index.html` — HTML, CSS und JavaScript zusammen, kein Build-Prozess,
keine Abhängigkeiten außer den Google Fonts.

**Gestaltung.** Farbwelt aus der Region statt Terrakotta-Klischee: Kalkstein (Noto),
Tinte (Reisetagebuch 1808), Feigenkaktus-Blüte, Zitrone. Schriften: Fraunces (Display),
IBM Plex Sans (Text), IBM Plex Mono (Zahlen und Etiketten).

**Kernstück** ist eine gezeichnete Sizilien-Karte in SVG mit beiden Routen als animierten,
gestrichelten Linien. Über zwei Schalter wechselt man zwischen Route A und B; Karte, Kennzahlen
und Etappenliste wechseln gemeinsam mit.

**Dreisprachigkeit.** Alle 72 Textbausteine liegen im Wörterbuch `I18N` am Ende der Datei,
getrennt nach `de`, `en`, `it`; die Etappendaten stehen im Objekt `ROUTES` ebenso dreisprachig.
Der Umschalter DE · EN · IT im Kopf tauscht alles ohne Neuladen. Die Sprache wird in der URL
gespeichert (`?lang=it`), sodass sich sprachspezifische Links verschicken lassen. Beim ersten
Besuch entscheidet die Browsersprache; unbekannte Sprachen landen auf Englisch.

Die italienische Fassung ist bewusst frei formuliert, kein Wort-für-Wort-Übertrag.
Giacomo sollte einmal drüberlesen.

**Fotos.** Zwei eigene Aufnahmen von Giacomo und Michael sind eingebunden:
`fotos/guides-meer.jpg` als Doppelporträt in der Guides-Sektion, `fotos/guides-mauer.jpg`
als Hauptbild der Galerie. Weitere Bilder werden als beschriftete Platzhalter angezeigt und
automatisch ersetzt, sobald die passende Datei im Ordner liegt.
Es wurden bewusst keine fremden Bilder aus dem Netz eingebunden — auf einer kommerziellen
Seite ist das ein Rechtsrisiko, und eigene Bilder aus Noto verkaufen ohnehin besser.

---

## 5. Offene Punkte

1. **Kontaktdaten** im Footer eintragen (E-Mail, Telefon sind Platzhalter).
2. **Stripe:** In `index.html` nach `STRIPE_PAYMENT_LINK_HIER_EINSETZEN` suchen. Im Stripe-Dashboard
   einen Zahlungslink über 300 € anlegen, URL einsetzen, beim Button `display:none` auf
   `display:block` ändern.
3. **Formular:** Zeigt bisher nur eine Bestätigung an und verschickt nichts. Schnellster Weg:
   Formspree — das `<form>`-Tag um `action="https://formspree.io/f/DEIN-CODE" method="POST"`
   ergänzen und den `submit`-Handler im Skript entfernen.
4. **Impressum und Datenschutz** ergänzen. In Österreich und Italien Pflicht, und für den
   deutschsprachigen Markt abmahnrelevant.
5. **Weitere Fotos** in `fotos/` legen: `noto.jpg`, `ortigia.jpg`, `modica.jpg`, `tisch.jpg`,
   `madonie.jpg`.
6. **Markenname prüfen:** „Trinacria Bici Express" verspricht Tempo, das Angebot verkauft
   Langsamkeit. Als ironischer Kontrast kann das funktionieren — aber bewusst entscheiden.
   Möglicher Untertitel: „Der langsamste Express Siziliens."

---

## 6. Veröffentlichen auf GitHub

Repository `trinacria-bici-express` anlegen, dann entweder per Drag-and-drop über
*„uploading an existing file"* hochladen, oder im Terminal:

```bash
cd trinacria-bici-express
git init && git add . && git commit -m "Erste Version"
git branch -M main
git remote add origin https://github.com/DEINNAME/trinacria-bici-express.git
git push -u origin main
```

Danach: Settings → Pages → Branch `main`, Ordner `/ (root)` → Save.
Live unter `https://DEINNAME.github.io/trinacria-bici-express/`.

---

## 7. Inhalt dieses Archivs

```
index.html              komplette dreisprachige Website
README.md               Kurzanleitung fürs Repository
PROJEKT-PROTOKOLL.md    dieses Dokument
.gitignore
fotos/
  guides-meer.jpg       Giacomo und Michael am Meer
  guides-mauer.jpg      Giacomo und Michael vor der Festungsmauer
```
