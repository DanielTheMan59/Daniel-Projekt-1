# Daniel-Projekt-1

## Trainings-Dashboard öffnen

Die Anwendung ist eine reine Browser-Datei ohne Backend.

### Option 1: Direkt öffnen
Öffne die Datei `training-dashboard.html` per Doppelklick im Browser.

### Option 2: Über die Startdatei öffnen
Öffne `index.html`. Diese Datei leitet automatisch auf `training-dashboard.html` weiter.

### Option 3: Mit lokalem Webserver öffnen
```bash
python3 -m http.server 8000
```

Danach im Browser öffnen:

```text
http://localhost:8000/
```

Die Trainingsdaten werden im Browser per `localStorage` gespeichert.
