# BariaTrack Website - Konfigurationshinweise

Diese Website befindet sich als Unterverzeichnis innerhalb von japana.github.io.

## Zugriff

Die BariaTrack-Seiten sind erreichbar unter:
- https://japana.github.io/bariatrack/

## Struktur

```
japana.github.io/
├── _config.yml          # Haupt-Jekyll-Konfiguration
├── bariatrack/          # BariaTrack Website
│   ├── index.md         # Hauptseite
│   ├── features.md      # Funktionen
│   ├── free-vs-pro.md   # Versionsvergleich
│   ├── getting-started.md # Erste Schritte
│   ├── faq.md           # Häufige Fragen
│   ├── privacy.md       # Datenschutz
│   ├── support.md       # Support & Hilfe
│   └── images/          # Bilder (Platzhalter)
│       └── README.md    # Anleitung für Bilder
```

## Theme

Die Website nutzt das `jekyll-theme-midnight` Theme der übergeordneten Site.

Für ein individuelles BariaTrack-Design könnte man:
1. Ein eigenes CSS-Stylesheet in `bariatrack/assets/css/` hinzufügen
2. Oder ein separates Repository für BariaTrack erstellen

## Lokales Testen

Um die Seiten lokal zu testen:

```bash
cd /workspace/project/japana.github.io
bundle exec jekyll serve
```

Dann im Browser öffnen: http://localhost:4000/bariatrack/

## Deployment

Die Website wird automatisch über GitHub Pages deployed, wenn Änderungen zum `main` Branch gepusht werden.
