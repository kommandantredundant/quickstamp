# Timestamps PWA

Eine minimalistische PWA zum Speichern von Zeitstempeln mit Tags.

## Deploy via Cloudflare Pages

1. Dieses Repo auf GitHub pushen
2. [Cloudflare Pages](https://pages.cloudflare.com) öffnen → **Create a project** → **Connect to Git**
3. Dieses Repository auswählen
4. Build-Einstellungen:
   - **Framework preset:** `None`
   - **Build command:** *(leer lassen)*
   - **Build output directory:** `/` (oder leer)
5. **Save and Deploy** — fertig.

Die App ist dann unter `https://dein-projekt.pages.dev` erreichbar.

## Auf Android installieren

1. App-URL in **Chrome** öffnen
2. Menü (⋮) → **„Zum Startbildschirm hinzufügen"**
3. Die App erscheint als Icon und läuft offline

## Features

- Zeitstempel per Tipp speichern
- Tags hinzufügen (Freitext + Vorschläge)
- Nach Tags filtern
- CSV-Export aller Einträge
- Offline-fähig (Service Worker)
- Daten lokal im Browser gespeichert (localStorage)
