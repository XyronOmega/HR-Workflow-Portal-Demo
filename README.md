# HR Workflow Portal – öffentliche Demo

Eigenständige statische Funktionsdemo des HR-Workflow-Portals. Keine Verbindung zu einem Backend, zu SAP, zu Microsoft 365 oder zu echten Beschäftigtendaten.

## Demo
Nach der Veröffentlichung über GitHub Pages: https://xyronomega.github.io/HR-Workflow-Portal-Demo/

## Funktionsumfang
- HR-Dashboard und Vorgangsverwaltung
- Fiktive Anträge und Statusänderungen
- Rollenansichten für Mitarbeitende, Vorgesetzte, HRBP, PA und Administration
- Genehmigungssimulation, Self-Service und Vertretungen
- Speicherung ausschließlich im Browser (localStorage)

## Sicherheit
**Nur Testdaten eingeben.** Rollenwechsel ist keine Authentifizierung. Keine echten Personal- oder Gesundheitsdaten in der öffentlichen Demo verwenden. Das private Hauptprojekt bleibt davon unabhängig.

## Veröffentlichen
GitHub: Settings → Pages → Build and deployment → Source: GitHub Actions.
Workflow: `.github/workflows/publish-demo.yml`. Jeder Push nach `main` löst die Veröffentlichung aus.
