# redaktionsschmiede.de

Tools der Redaktionsschmiede. Statische Seite ohne Build-Schritt, Lizenz: Apache-2.0.

## Struktur

- `index.html` – Startseite
- `arbeit/` – Fälle und Arbeitsproben
- `blog/` – Blog (je Text ein Ordner, z. B. `blog/metadaten-ueberzeugung/`)
- `masker/` – Secret Masker, läuft vollständig im Browser
- `impressum/`, `datenschutz/` – Rechtstexte
- `assets/site.css` – gemeinsames Stylesheet
- `_headers` – Sicherheits-Header (u. a. Content-Security-Policy für den Masker)

## Bilder

Diese Dateien werden von den Seiten erwartet und fehlen im Repo, solange sie nicht ergänzt sind (die Seiten blenden fehlende Bilder aus):

- `img/portrait.jpg`
- `arbeit/img/emden.jpg`
- `arbeit/img/regionalindex-karte.jpg`
