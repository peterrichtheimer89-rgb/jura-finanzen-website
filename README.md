# Jura.Finanzen | Website von Valentin Kirsch

Statische Website, gehostet bei Netlify. Jede Änderung auf `main` geht automatisch online.

## Aufbau
- `index.html`: die ganze Startseite (Rechner, Themen, Quiz, Über mich, Bewertungen, FAQ, Kontakt)
- `impressum.html`, `datenschutz.html`, `danke.html`
- `erfolge.js`: Erfolgsgeschichten (nur mit schriftlicher Einwilligung der Kunden), Bilder/Videos in `assets/erfolge/`
- `assets/`: Bilder, Schrift, Icons
- `netlify.toml`: Netlify-Einstellungen

## Kontaktformular
Läuft über Netlify Forms (Formularname `kontakt`).
- In Netlify unter Forms > Settings muss „Find forms on your pages“ eingeschaltet sein.
  Zusätzlich steht in `netlify.toml` `ignore_html_forms = false`.
- E-Mail-Benachrichtigung: Forms > Notifications > Add notification.
- Klappt das Absenden nicht, öffnet die Seite als Ersatz das Mailprogramm des Besuchers.

## Netlify-Credits
Kostenloser Tarif: 300 Credits im Monat, jede Veröffentlichung auf `main` kostet 15.
Änderungen deshalb gesammelt hochladen.
