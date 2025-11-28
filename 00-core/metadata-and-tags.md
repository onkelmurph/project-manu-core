# Metadata & Tags – Wie Inhalte beschrieben werden

Dieses Dokument definiert, wie Inhalte innerhalb des Repos mit Metadaten und Tags versehen werden sollen,
damit KIs sie besser einordnen und wiederfinden können.

---

## 1. Einfache Metadaten im Kopfbereich

Bei größeren Dateien (z. B. Konzepte, HowTos, Wissenssammlungen) kann ein einfacher „Kopfbereich“
am Anfang stehen – optional, aber sehr hilfreich.

Beispiel:

```markdown
---
typ: wissensartikel
bereich: home-assistant
priorität: hoch
status: stabil
version: 1.0
zuletzt_aktualisiert: 2025-11-28
---

# Titel des Dokuments
...
```

**Empfehlung:**  
Nur dort einsetzen, wo es wirklich Sinn macht (03-knowledge, 02-projects).

---

## 2. Tags in Texten

Am Ende einer Datei können einfache Tag-Listen stehen:

```markdown
**Tags:** #home-assistant #automation #licht #workflow
```

Diese Tags sollen:
- möglichst in Kleinbuchstaben,
- ohne Umlaute (ö → oe etc. optional),
- ohne Leerzeichen (stattdessen Bindestriche) sein.

---

## 3. Wozu Metadaten und Tags?

Sie helfen KIs dabei:
- bestimmte Themen schneller zu finden,
- ähnliche Inhalte zu clustern,
- Redundanzen zu erkennen,
- passende Dokumente zu einem Prompt zu wählen.

---

## 4. Kategorien

Einige sinnvolle Standard-Kategorien:

- `home-assistant`
- `webdesign`
- `schreiben`
- `persona`
- `projekte`
- `theologie`
- `beziehungen`
- `technik`
- `organisation`

Diese Kategorien können auch in Unterordnern als Struktur dienen.

---

## 5. Minimal-Variante

Wenn keine Zeit ist für komplexe Metadaten:
- lieber wenige Tags als gar keine
- lieber ein Satz am Anfang:  
  „Dieses Dokument erklärt … und richtet sich an …“

---

## 6. Ziel

Metadaten sollen **helfen**, nicht belasten.  
Sie sind ein Werkzeug für bessere KI-Kontextauswahl – kein Selbstzweck.
