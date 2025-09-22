## Shared Responsibility Model

```mermaid
flowchart LR
    Kunde["👤 Kunde<br/>Identitäten, Daten, Applikationen"] 
    Provider["☁️ Provider<br/>Rechenzentrum, Netzwerk, Hardware"]
    Beide["🤝 Gemeinsam<br/>OS, Patching, Konfiguration"]

    Kunde --> Beide
    Provider --> Beide
