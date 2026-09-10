# CONTEXT.md for VW T6 Innenverkleidung

## Purpose
Erstellung einer Schablone (Schnittmuster) für die Innenverkleidung eines VW T6 Fahrzeugs aus 4mm Pappelsperrholz. Das Schnittmuster dient als Vorlage für die CNC- oder Laserfertigung der Verkleidungsplatten.

## Current State
Das Projekt besteht derzeit aus einer HTML-Datei `schnittmuster-3.html`, die das Schnittmuster darstellt. Es gibt noch keine angepassten Versionen für die Fertigung; die Datei ist im Rohzustand vom ursprünglichen Entwurf. Die Ordnerstruktur enthält `code/`, `docs/`, `tests/` (leer) sowie die Hauptdatei.

## Architecture
Einfache Architektur: Eine einzelne HTML-Datei, die mittels eines Browsers betrachtet werden kann. Eventuell können CSS und JavaScript zur interaktiven Anzeige hinzugefügt werden, aber derzeit ist es reine statische Markup.

## Technologies
- HTML5 (für das Schnittmuster)
- Optional: CSS3, JavaScript (falls interaktive Vorschau gewünscht)
- Keine Frameworks oder externen Bibliotheken derzeit eingesetzt.

## Components
- `schnittmuster-3.html`: Hauptdatei mit dem Schnittmuster.
- `docs/`: Platzhalter für zusätzliche Dokumentation (z.B. Fertigungshinweise).
- `code/`: Platzhalter für eventuelle Skripte (z.B. zur Maßenberechnung).
- `tests/`: Platzhalter für Testskripte (derzeit nicht genutzt).

## Important Files
- `schnittmuster-3.html`: Enthält das eigentliche Schnittmuster; zentrale Datei für die Fertigung.
- `README.md`: Projektbeschreibung und Nutzungshinweise.
- CONTEXT.md: Dieses Dokument.

## Interfaces
- Keine programmatischen Schnittstellen. Das Schnittmuster wird an die Fertigungsabteilung übergeben (evtl. als Datei exportiert oder direkt geöffnet).
- Bei Nutzung eines Browsers zur Vorschau: Standard-HTML-Rendering über DOM.

## Constraints
- Das Sperrholz hat eine Dicke von 4 mm; das Schnittmutter muss dies berücksichtigen (Kerf bei Laser-/CNC-Schnitt).
- Die Maße müssen zum VW T6 Innenraum passen; Anpassungen am Original können nötig sein.
- Die Datei darf keine urheberrechtlich geschützten Inhalte enthalten; das aktispiel ist eigen erstellt.
- Beim Laserschneiden müssen Schnittlinien entsprechend farblich gekennzeichnet sein (falls die Fertigungssoftware dies erfordert).

## Known Problems
- Das aktuelle Schnittmuster ist nicht auf die spezifische Fertigungsmaschine kalibriert (z.B. Laserleistung, Schnittgeschwindigkeit).
- Es gibt noch keine Überprüfung, ob alle Teile tatsächlich aus dem 4 mm Pappelsperrholz ausgeschnitten werden können (Brücken, zu feine Strukturen).
- Die HTML-Datei enthält möglicherweise unnötiges Markup, das die Klarheit reduziert.

## Development Rules
- Änderungen am Schnittmuster sollten zunächst in einer Kopie gespeichert werden (z.B. `schnittmuster-3_v2.html`), um das Original zu bewahren.
- Nach jeder Änderung ist eine Sichtprüfung im Browser empfohlen, um die Geometrie zu validieren.
- Bei Hinzufügen von CSS/JS darauf achten, dass die Datei weiterhin in gängigen Browsern öffnet.
- Dokumentation wichtiger Maße oder Anpassungen in diesem CONTEXT.md oder in einer separaten Datei unter `docs/`.

## Deployment
Das fertige Schnittmuster wird als HTML-Datei an die Fertigung weitergegeben. Dort wird es je nach Maschinenkonzept entweder direkt geöffnet oder in das jeweilige Format (SVG, DXF etc.) konvertiert. Die derzeitige Ausgabe ist HTML; bei Bedarf muss ein Konvertierungsschritt eingefügt werden.

## GitHub
Das Projekt ist derzeit nicht mit einem GitHub-Repository verbunden. Beim ersten Anlegen eines Repos könnte hier die URL und der Hauptbranch eingetragen werden.