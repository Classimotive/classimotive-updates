# Classimotive Updates

Signierte Firmware für das Classimotive Gauge, abgerufen von der Classimotive-App unter
`https://updates.classimotive.com/gauge/manifest.json`.

- Nur `manifest.json` und `.bin`-Dateien, die mit `tools/make_manifest.py --key …` signiert sind.
- Ein Gauge nimmt nur Firmware mit gültiger Signatur an (ECDSA P-256).
- Inhalt wird aus dem Firmware-Repo mit `tools/release_fw.ps1` erzeugt, nicht von Hand ändern.
