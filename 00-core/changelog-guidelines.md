# Changelog & Änderungsrichtlinien

Dieses Dokument definiert, wie Änderungen an wichtigen Dateien
im Project Manu Core sinnvoll dokumentiert werden können.

Es ist keine Pflicht, aber eine Empfehlung – vor allem für große Anpassungen.

---

## 1. Wann ein Changelog sinnvoll ist

- bei größeren Umbauten in der Struktur,
- bei Änderungen an Kernlogiken (Core, Persona v4, Modes),
- bei Löschungen von Inhalten,
- bei Zusammenführung von Dateien,
- bei maßgeblichen stilistischen Neuausrichtungen.

Kleine Tippfehler oder Mikroanpassungen brauchen keinen Eintrag.

---

## 2. Form eines einfachen Changelogs

Eine Datei wie z. B.  
`00-core/changelog.md` (kann später ergänzt werden) könnte Einträge enthalten wie:

```markdown
## 2025-11-28

- persona-v4.md von v3 auf v4 aktualisiert (Kernpersona erweitert).
- persona-modes.md um Prioritätenliste ergänzt.
- metadata-and-tags.md erstellt, um Tagging zu klären.

## 2025-12-05

- knowledge-entry-template.md hinzugefügt.
- context-strategy.md überarbeitet (Kontextauswahl präzisiert).
```

---

## 3. Kurzform in Dateien selbst

Alternativ können relevante Dateien am Ende einen Abschnitt haben:

```markdown
---

**Änderungsverlauf (Kurzform)**  
- 2025-11-28: erste Version erstellt  
- 2025-12-10: Abschnitt „Kontextstrategie“ ergänzt
```

---

## 4. Ziel

Ziel ist nicht Bürokratie,
sondern:
- Nachvollziehbarkeit,
- Klarheit,
- und die Möglichkeit, Entwicklungen im System zu verstehen.

Der Changelog soll helfen,  
insbesondere bei Persona- und Core-Dateien zu wissen:
**Was war wann der Stand der Dinge?**
