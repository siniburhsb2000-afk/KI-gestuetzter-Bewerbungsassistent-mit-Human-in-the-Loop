# Prompt: CV-Stellen-Matching

**Eingaben:** `{{STELLENANZEIGE}}`, `{{CV}}`, Gewichtung aus `config/suchparameter.json`

**Aufgabe**
1. Zerlege die Anzeige in Muss- und Kann-Anforderungen.
2. Bewerte für jede Anforderung: erfüllt / teilweise / nicht erfüllt, mit Beleg aus dem CV.
3. Berechne einen Score von 0–10 je Kategorie (fachlich, Erfahrung, Soft Skills, Rahmenbedingungen) und gewichte ihn.
4. Ab Gesamtscore ≥ Schwellenwert (Standard 7): `"weiter": true`

**Ausgabe (JSON)**
```json
{
  "stelle": "", "unternehmen": "",
  "anforderungen": [{"text": "", "typ": "muss|kann", "status": "erfuellt|teilweise|nicht", "beleg": ""}],
  "kategorie_scores": {"fachliche_anforderungen": 0, "erfahrung": 0, "soft_skills": 0, "rahmenbedingungen": 0},
  "gesamt_score": 0,
  "weiter": false,
  "begruendung": ""
}
```
