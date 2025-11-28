# Datei- und Ordnerkonventionen – Project Manu Core

Dieses Dokument legt fest, **wie** Dateien und Ordner in diesem Repo benannt
und strukturiert werden sollen.

Es dient dazu:
- Chaos zu vermeiden,
- Wiederauffindbarkeit zu sichern,
- KIs und Menschen eine klare Orientierung zu geben.

---

## 1. Grundstruktur

Top-Level-Ordner:

- `00-core` – Grundlagen, Regeln, Konventionen, Meta
- `01-persona` – Manu-Persona, Stil, Modus-System
- `02-projects` – Konkrete Projekte, Entwürfe, Arbeitsstände
- `03-knowledge` – Wissen, Anleitungen, Erklärungen, Methoden
- `04-assets` – Bilder, Medien, zusätzliche Ressourcen

Diese Ordnung soll stabil bleiben.

---

## 2. Benennung von Dateien

**Grundprinzipien:**

1. **Klarheit vor Kreativität**  
   Dateinamen sollen verständlich sein, bevor sie „schön“ sind.

2. **Kürze, aber eindeutig**  
   Keine Roman-Titel – aber auch keine Abkürzungsmonster.

3. **Sprache konsistent**  
   Deutsch oder Englisch im Dateinamen – Mischungen nur, wenn logisch.

---

### 2.1 Muster

Empfohlene Muster:

- `thema-kurzbeschreibung.md`
- `bereich-unterspezifikation-v1.md`
- `projektname-konzept.md`
- `projektname-flow.md`
- `howto-<thema>.md`
- `faq-<thema>.md`

---

## 3. Versionierung

Wenn mehrere Versionen einer Datei parallel existieren sollen:
- Suffix verwenden: `-v1`, `-v2`, `-v3`  
- ältere Versionen optional in Unterordner `archive/` verschieben

Beispiele:
- `persona-v4.md` (aktive Version)
- `persona-v3-archive.md` (falls noch relevant)

---

## 4. Ordner innerhalb von 02–04

### 4.1 `02-projects`

Strukturbeispiel:

- `02-projects/web-dekanat/`
- `02-projects/home-assistant/`
- `02-projects/crowdfunding-mona/`

Innerhalb:
- `readme.md` – kurze Erklärung des Projekts
- Unterdateien (z. B. `texte-landingpage.md`, `flows-ha.md`)

---

### 4.2 `03-knowledge`

Strukturbeispiel:

- `03-knowledge/home-assistant/`
- `03-knowledge/webdesign/`
- `03-knowledge/schreiben/`

Dateien:
- `grundlagen.md`
- `best-practices.md`
- `faq.md`
- `checklisten.md`

---

### 4.3 `04-assets`

Strukturbeispiel:

- `04-assets/web/`
- `04-assets/ha-screenshots/`
- `04-assets/logos/`

Dateien möglichst mit:
- Projektbezug
- kleinem, sprechendem Namen

---

## 5. Indizes und Übersicht

Wo sinnvoll, sollen Index-Dateien verwendet werden:

- `index.md` auf Root-Ebene (bereits vorhanden)
- `readme.md` in Unterordnern
- `*-index.md` für Sammlungen (z. B. `knowledge-index.md`)

Das Ziel ist, dass eine KI mit wenigen Index- oder Readme-Dateien
das gesamte Repo strukturverstehen kann.

---

## 6. Keine Duplikate

Inhalte sollen nicht mehrfach in unterschiedlichen Dateien liegen.

Wenn Inhalte ähnlich sind:
- eine Quelle wählen,
- andere Dateien darauf verweisen (z. B. „Siehe: `03-knowledge/home-assistant/grundlagen.md`“).

---

## 7. Ziel

Diese Konventionen sollen:
- die Einstiegshürde senken,
- die Evolution des Repos erleichtern,
- KIs und Menschen helfen, nicht in Dateiwüsten zu landen.
