# Kontext-Strategie – Wie KIs Inhalte aus dem Repo auswählen sollen

Dieses Dokument beschreibt, wie KIs sinnvoll Kontext aus dem Repository ziehen sollen,
ohne alles blind einzulesen oder Wichtiges zu übersehen.

---

## 1. Grundprinzip

KIs sollen dieses Repo wie eine **Bibliothek mit Regalen** behandeln –  
nicht wie eine lose Dateiablage.

Das heißt:
1. Erst Orientierung holen (Index, Readmes).
2. Dann gezielt Inhalte wählen.
3. Dann bei Bedarf nachladen.

---

## 2. Reihenfolge der Kontextsuche

1. `index.md` (Root) – grober Aufbau  
2. `00-core/core-overview.md` – Grundlogik  
3. Ordnerspezifische `readme.md` / `index`-Dateien  
4. passende Themenordner in `03-knowledge` oder `02-projects`  
5. Detaildokumente (HowTos, Konzepte, Flows)

---

## 3. Auswahlstrategie

Je nach Aufgabe:

### 3.1 Schreiben / Textentwicklung
- Persona laden (01-persona),
- ggf. Projektordner (02-projects),
- relevante Wissens-Artikel (03-knowledge).

### 3.2 Technik / Setup / Fehler
- `03-knowledge`-Bereich zum Thema,
- projektbezogene Dateien in `02-projects`,
- ggf. Screenshots/Assets zur Orientierung.

### 3.3 Kreativ / Design
- Projektordner,
- Persona-Stilmodule,
- evtl. Assets als Referenz.

---

## 4. Begrenzung von Kontext

KIs sollen:
- nicht „alles auf einmal“ laden,
- lieber gezielt 3–8 Dateien wählen,
- basierend auf:
  - Ordnerstruktur
  - Dateinamen
  - vorhandenen Index-Infos
  - Tags / Metadaten

---

## 5. Aktualität

Wenn es mehrere Dateien zu ähnlichen Themen gibt:
- den Versionshinweis beachten (`v1`, `v2`, Datum, `archiv`/`archive`),
- die **jüngste, aktive** Datei priorisieren.

---

## 6. Ziel

KIs sollen lernen, dieses Repo effektiv zu nutzen,
statt sich im Kontextfenster zu verheddern.

Eine gute Kontextstrategie bedeutet:
- schneller zum Punkt,
- weniger Missverständnisse,
- besser passende Antworten.
