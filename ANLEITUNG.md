# ANESIS SOLTAU – fertige Website

Das ist die fertige Website, nicht der Quelltext. Du brauchst hier nichts zu installieren oder zu bauen.

## So kommt sie zu GitHub

1. Dein Repo öffnen: `seitenwerkde/Website-ReviewAnesis1`
2. Oben auf **Add file** → **Upload files** klicken
3. Alle Dateien aus diesem Ordner hier reinziehen – auch die Ordner
   `assets`, `speisekarte`, `impressum`, `datenschutz` und `downloads`
4. Unten auf **Commit changes** klicken
5. Eine bis zwei Minuten warten, dann öffnen:
   **https://seitenwerkde.github.io/Website-ReviewAnesis1/**

Danach erscheint die echte Website und nicht mehr nur die Projektbeschreibung.

## Was drin ist

- `index.html` – Startseite mit Menü, Empfehlungen, Galerie, Fragen und Anfahrt
- `speisekarte/`, `impressum/`, `datenschutz/` – die drei weiteren Seiten
- `assets/` – Bilder, Schriften und das Programm der Seite
- `downloads/anesis-speisekarte.pdf` – die Speisekarte als PDF
  (auf der Website ist kein PDF-Knopf, wie gewünscht)
- `.nojekyll` – versteckte Datei, bitte mit hochladen; sie sagt GitHub,
  dass die Dateien unverändert ausgeliefert werden sollen

## Wichtig zu wissen

- Die Dateien kann man **nicht per Doppelklick** ansehen. Diese Art Website läuft
  nur über eine Web-Adresse (GitHub oder die Vorschau hier in Lovable).
- Adressen und Telefonnummern stehen zentral in `src/config/restaurant.ts`
  im Quelltext-Repo – dort änderst du sie, wenn sich etwas ergibt.
