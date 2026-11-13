# Taxi-AC 24/7 Dortmund

Statische Website für Taxi-AC 24/7 in Dortmund.

**Live-Website:** https://www.taxikreisdortmund.de/

## Seiten

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite und Leistungsübersicht |
| `flughafentransfer-dortmund.html` | Flughafentransfers und Festpreise |
| `krankenfahrten-dortmund.html` | Kranken-, Dialyse- und Rehafahrten |
| `grossraumtaxi-dortmund.html` | Großraumtaxi |
| `taxi-dortmund-24h.html` | Taxi-Service rund um die Uhr |
| `impressum.html` | Impressum |
| `datenschutz.html` | Datenschutzerklärung |

## Projektstruktur

```text
.
├── index.html
├── flughafentransfer-dortmund.html
├── krankenfahrten-dortmund.html
├── grossraumtaxi-dortmund.html
├── taxi-dortmund-24h.html
├── impressum.html
├── datenschutz.html
├── style.css
├── fonts/
├── CNAME
├── robots.txt
├── sitemap.xml
├── favicon.svg
├── favicon-48.png
├── favicon-192.png
├── favicon-512.png
├── hero.jpg
└── taxi2.jpg
```

## Technik

- Statische Website mit HTML und CSS
- Hosting und Veröffentlichung über GitHub Pages
- Gemeinsames Design über `style.css`
- SEO-Metadaten und strukturierte Daten (Schema.org) in den HTML-Dateien
- Schriftarten Bebas Neue und DM Sans lokal im Verzeichnis `fonts/` (nach abgeschlossener Umstellung)
- Eigene Domain: `www.taxikreisdortmund.de`

## Veröffentlichung

Die Website wird über GitHub Pages aus dem konfigurierten Branch und Verzeichnis veröffentlicht.

Änderungen am veröffentlichten Quellcode werden nach dem Push in den konfigurierten Veröffentlichungszweig von GitHub Pages übernommen.

Die Domain-Konfiguration wird über die Datei `CNAME` und die DNS-Einstellungen des Domain-Anbieters verwaltet.

## Pflegehinweise

- Preise immer auf der Website, in den SEO-Metadaten und in den strukturierten Daten konsistent halten.
- Nach Preisänderungen insbesondere `index.html` und `flughafentransfer-dortmund.html` prüfen.
- Neue Unterseiten in Navigation, Sitemap und dieser Übersicht ergänzen.
- Externe Dienste (z. B. Tracking, Karten oder eingebettete Inhalte) nur nach Prüfung der Datenschutzanforderungen ergänzen.
- Keine Passwörter, API-Schlüssel, Zugangsdaten oder sonstigen vertraulichen Informationen in dieses Repository committen.
