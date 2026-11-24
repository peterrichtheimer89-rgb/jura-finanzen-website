# Jura.Finanzen | Website von Valentin Kirsch

Statische Website, gehostet bei Netlify. Jede Änderung auf `main` geht automatisch online.

## Aufbau
- `index.html`: die ganze Startseite (Rechner, Themen, Quiz, Über mich, Bewertungen, FAQ, Kontakt)
- `impressum.html`, `datenschutz.html`, `danke.html`
- `erfolge.js`: Erfolgsgeschichten (nur mit schriftlicher Einwilligung der Kunden), Bilder/Videos in `assets/erfolge/`
- `assets/`: Bilder, Schrift, Icons
- `netlify.toml`: Netlify-Einstellungen

## Kontaktformular
Läuft über Netlify Forms (Formularname `kontakt`). Benachrichtigung per E-Mail unter
Netlify > Site > Forms > Form notifications einstellen.
