# Feuerphönix Leaderschaft – GitHub Pages

Statische GitHub-Pages-Basis der Leaderschafts-Web-App.

## Wichtig
Die enthaltene Anmeldung ist **nur eine Demo-Oberfläche**. Für den produktiven Betrieb dürfen Benutzername/Passwort nicht in JavaScript gespeichert werden.

## Empfohlener produktiver Aufbau
- Frontend: GitHub Pages
- Authentifizierung: Supabase Auth
- Datenbank: Supabase PostgreSQL
- Rollen: `leader`, `co_leader`, `verwaltung`
- Row Level Security (RLS) für alle Tabellen

## GitHub Pages
Repository anlegen → Dateien hochladen → Settings → Pages → Deploy from branch → `main` / root.

Danach ist die Seite unter `https://DEINNAME.github.io/REPOSITORY/` erreichbar.
