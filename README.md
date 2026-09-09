# Mediahub
Plattform um Video und Fotos Hochzuladen und Abzurufen für MEDV Media Team

## Repository Struktur

´´´´
.
├── docs/                   # Anforderungen, Architektur, Entscheidungen
│   ├── 00-tech-stack.md
│   ├── 01-idee-und-zweck.md
│   ├── 02-rollen-und-nutzer.md
│   ├── 03-features.md
│   ├── 04-datenmodell.md
│   ├── 05-mobile-spezifika.md
│   ├── 06-nicht-funktionale-anforderungen.md
│   └── adr/                # Architecture Decision Records
├── backend/                # .NET 9 Solution (Clean Architecture)
│   ├── src/
│   │   ├── Domain/
│   │   ├── Application/
│   │   ├── Infrastructure/
│   │   └── Api/
│   └── tests/
├── mobile/                 # React Native / Expo App
├── deploy/                 # docker-compose, Caddyfile, Backup-Skripte
└── .github/workflows/      # CI/CD

´´´´
