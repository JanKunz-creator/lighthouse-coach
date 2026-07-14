# Lumi English Adventure PWA v0.4

Diese Version enthält die vollständige Task-Bank für Klasse 6, Unit 1 (`tasks-g6-u1.json`) und nutzt diese Aufgaben direkt in der App.

## Upload zu GitHub

Alle Dateien aus diesem Ordner in das Repository hochladen und vorhandene Dateien ersetzen:

- `index.html`
- `manifest.webmanifest`
- `service-worker.js`
- `tasks-g6-u1.json`
- `icons/`

Nach dem Commit wird GitHub Pages automatisch aktualisiert. Auf dem iPad die Seite danach einmal neu laden. Wenn noch die alte Version erscheint, Safari-Websitedaten für die GitHub-Pages-Adresse löschen.


## v0.4.1
Die Unit-1-Task-Bank ist zusätzlich direkt in `index.html` eingebettet. Dadurch startet die App auch dann, wenn die JSON-Datei beim ersten Laden noch nicht erreichbar ist.
