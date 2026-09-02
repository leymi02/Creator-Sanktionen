CREATOR MANAGEMENT – SUPABASE VERSION

Diese Version ist mit Supabase verbunden.

Supabase:
- URL: https://sivdyarxpeuvvpdmzycw.supabase.co
- Tabelle: CreatorVerwaltung
- Verwendet wird ausschließlich der Publishable Key.
- KEIN service_role/Secret Key ist in der Website enthalten.

So funktioniert es:
1. Besucher öffnen die Seite normal und können Inhalte lesen.
2. Unten rechts gibt es "Admin Login".
3. Mit dem in Supabase Authentication angelegten Admin-Konto einloggen.
4. Danach werden Bearbeiten-/Design-Funktionen sichtbar.
5. Änderungen werden in der Tabelle "CreatorVerwaltung" gespeichert und sind für alle Besucher sichtbar.

Gespeicherte content_key-Werte:
- sanctions     -> Sanktionskatalog
- instructions  -> Creator-Anleitungen
- site_design   -> gemeinsames Seitendesign

WICHTIG:
Die Tabelle ist aktuell leer. Beim ersten Aufruf werden beim Sanktionskatalog die mitgelieferten JSON-Daten angezeigt.
Sobald du als Admin eine Änderung speicherst, wird automatisch der entsprechende Datensatz in Supabase erstellt.

Dateien für GitHub Pages:
- index.html
- Sanktionskatalog.html
- Creator_Anleitung.html
- streamer-sanktionen.json

Alle vier Dateien direkt in den Hauptordner deines GitHub-Repositories hochladen.
