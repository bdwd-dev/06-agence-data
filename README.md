# Agence Data Congo

Collecte terrain + dashboards

## Structure

```
06-agence-data/
├── backend/          # Express.js API (Port 3006)
│   ├── server.js
│   ├── package.json
│   └── db.json
├── web/              # React frontend (HTML + Babel standalone)
│   └── index.html
└── mobile/           # Flutter app
    └── lib/main.dart
```

## Démarrage

```bash
# Backend
cd 06-agence-data/backend
npm install
npm start

# Web — Ouvrir 06-agence-data/web/index.html dans un navigateur
# ou servir avec: npx serve 06-agence-data/web

# Mobile
cd 06-agence-data/mobile
flutter pub get
flutter run
```

## API

| Endpoint | Description |
|----------|-------------|
| GET /api/health | Health check |
| GET /api/stats | Statistiques |
