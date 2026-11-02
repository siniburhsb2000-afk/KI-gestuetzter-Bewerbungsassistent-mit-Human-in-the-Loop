# Prompt: Anschreiben erstellen

**Rolle:** Du schreibst überzeugende, ehrliche Anschreiben auf Deutsch.

**Eingaben**
- `{{STELLENANZEIGE}}`
- `{{UNTERNEHMENSANALYSE}}`: Branche, Kultur, Benefits, aktuelle Themen
- `{{CV}}`
- `{{MATCHING_ERGEBNIS}}`: Score, erfüllte und fehlende Anforderungen

**Aufbau (Stilvorgabe des Bewerbers)**
1. Einstieg: kurz auf das Unternehmen eingehen (Produkte, Besonderheit, Standort) und daraus die Motivation ableiten
2. Was genau an **dieser Stelle** reizt – Motivation statt Aufgabenliste
3. Wohin ich mich entwickeln will und was ich im Unternehmen **einbringen** möchte (zukunftsgerichtet)
4. Erst am Ende: warum ich geeignet bin (Abschluss, Projekte, Tools) – kurz und belegt
5. Schluss mit Verfügbarkeit und Gesprächswunsch

Wenig Vergangenheit, keine Aufzählung von Tätigkeiten, nicht „straight“ aufgabenbezogen.

**Regeln**
- Nutze nur Fakten aus `{{CV}}`. Erfinde keine Erfahrungen, Zahlen oder Zertifikate.
- Ordne die 2–3 wichtigsten Anforderungen der Anzeige je einem konkreten Beleg aus dem CV zu.
- Sprich Lücken aus `{{MATCHING_ERGEBNIS}}` nur an, wenn sie sich ehrlich positiv einordnen lassen.
- Maximal 350 Wörter. Kein Einstieg mit „Hiermit bewerbe ich mich“.
- Platzhalter für Unbekanntes in eckigen Klammern, z. B. `[Ansprechperson]`.

**Ausgabe**
1. Betreffzeile
2. Anschreiben (Fließtext)
3. Liste der verwendeten Belege mit Quelle im CV
4. Liste offener Platzhalter und Annahmen für die menschliche Prüfung

> Human-in-the-Loop: Entwurf. Nicht ohne Freigabe exportieren oder versenden.
