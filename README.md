# KI-gestuetzter Bewerbungsassistent mit Human-in-the-Loop

Automatisierter Workflow zur Jobsuche, CV-Stellen-Matching, Unternehmensanalyse 
und Erstellung individueller Bewerbungsdokumente – geplante Umsetzung mit n8n, 
KI-Agenten und inkludiertes HITL.

## Was das System leisten soll:

- **Automatisierte Jobsuche** über Google Jobs
- **CV-Stellen-Matching** mit Scoring (Schwellenwert ≥ 7/10)
- **Unternehmensanalyse** (Branche, Kultur, Benefits)
- **Dokumentengenerierung** (Anschreiben, CV)
- **Human-in-the-Loop** – Freigabe vor jedem Export

## Was das System NICHT tut

- Kein autonomes Versenden von Bewerbungen
- Keine finalen Karriereentscheidungen durch die KI
- Kein Ersatz menschlicher Urteilsfähigkeit

## Tech-Stack

| Tool | Zweck |
|------|-------|
| n8n | Workflow-Orchestrierung |
| Claude / ChatGPT | Textgenerierung & Matching |
| Python | Datenverarbeitung & Scoring |
| JSON / Markdown | Konfiguration |

## n8n-Workflow
Platzhalter gesetzt für WebhookID: "YOUR_WEBHOOK_ID_HERE"

<img width="1207" height="617" alt="n8n-Worfklow-Screenshot" src="https://github.com/user-attachments/assets/fb2fb020-e9d1-46fc-8c5e-564dfee659c9" />


## Status/Learnings
Workflow dezimiert und radikal verschlankt, denn bisheriges Learning: Starte zu Beginn smart und lean im Wofkflowaufbau und maximiere damit das Verständnis.
