# Prüfungstrainer Mathe 10II/III

Interaktive Web-App mit den Aufgaben der Abschlussprüfungen Mathematik II (bayerische Realschule, 2018–2025), sortiert nach Themen, mit ausführlichen, schrittweise einblendbaren Lösungen.

- läuft komplett im Browser, ohne Server, ohne Anmeldung, ohne Tracking
- funktioniert nach dem ersten Aufruf auch **offline**
- lässt sich auf Handy/Tablet als App auf den Startbildschirm legen

## Veröffentlichen mit GitHub Pages

1. Auf github.com ein neues Repository anlegen (z. B. `pruefungstrainer`).
2. „Add file“ → „Upload files“ → den **Inhalt** dieses Ordners hineinziehen
   (index.html, data.js, sw.js, manifest.webmanifest, .nojekyll sowie die Ordner img, katex, icons) → „Commit changes“.
3. „Settings“ → „Pages“ → Source: „Deploy from a branch“, Branch: `main`, Ordner: `/ (root)` → „Save“.
4. Nach 1–2 Minuten ist die App erreichbar unter
   `https://<benutzername>.github.io/pruefungstrainer/`

## Aktualisieren

Geänderte Dateien einfach erneut hochladen. Wenn sich Aufgaben ändern, muss auch `sw.js`
mit hochgeladen werden (neue Versionsnummer), damit die Geräte der Schüler die neue Fassung laden.
