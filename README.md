# Mystery Serien – statisches Stremio-Addon

## Installation über GitHub Pages
1. Neues öffentliches GitHub-Repository erstellen, z. B. `mystery-serien-stremio`.
2. Den Inhalt dieses Pakets hochladen. `manifest.json` muss direkt im Repository-Stamm liegen.
3. GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. Nach der Veröffentlichung lautet die Manifest-URL ungefähr:
   `https://DEINNAME.github.io/mystery-serien-stremio/manifest.json`
5. Diese URL in Stremio als Add-on-URL hinzufügen.

Struktur:
- manifest.json
- catalog/series/mystery-serien.json

Das Addon liefert nur den Katalog. Metadaten/Streams kommen weiterhin von deinen anderen Stremio-Addons.
