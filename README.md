## Anleitung 

### Erstellen eines Beitrages

Beiträge werden als Ordner unter `posts/` abgelegt. Jeder Beitrag besteht aus einer Datei (`.md` oder `.qmd`) und allen zugehoerigen Dateien (Bilder, Daten, PDFs).

Es biete sich an, lokal einen Ordner zu erzeugen, z. B. so:

```
mein_beitrag/
  mein_beitrag.qmd
  abbildung1.png
  daten.csv
```

Wichtig: Alle Abhaengigkeiten (Bilder, PDFs, Daten) kommen in denselben Beitrag-Ordner. Kommt der Beitrag ohne Zitation aus, kann ein einfaches Markdown (`.md`) verwendet werden. Sollen Zitation erfolgen und ein automatisiertes Literaturverzeichnis generiert werden, muss Quarto-Markdow (`.qmd`) verwendet werden. Siehe als Beispiel: `posts\MFA\MFA.qmd`

### Upload eines Beitrages

1. Den gesamten Beitrag-Ordner unter `posts/` hochladen.
2. Commit und Push nach `main`.
3. Die GitHub Action rendert automatisch die HTML-Dateien nach `docs/`.