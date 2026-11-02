# Workflow-Ablauf (lean)

```
Jobsuche (Google Jobs, config/suchparameter.json)
   → Matching (prompts/matching_scoring.md), Score ≥ 7?
       nein → verwerfen / Log
       ja   → Unternehmensanalyse
            → Anschreiben-Entwurf (prompts/anschreiben_generierung.md)
            → Selbstprüfung (prompts/anschreiben_analyse.md)
            → HITL-Freigabe ✋ (Mensch prüft, ändert, gibt frei)
            → Export (kein automatischer Versand)
```

## HITL-Checkliste vor Freigabe
- [ ] Alle Fakten stimmen mit dem CV überein
- [ ] Platzhalter `[...]` ersetzt
- [ ] Ansprechperson und Firmenname korrekt
- [ ] Ton passt zu mir und zum Unternehmen
- [ ] Gehalt/Eintrittstermin, falls gefordert
