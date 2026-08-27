---
title: "LinkAnnotation"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt entweder einen Hypertext‑Link zu einem Ziel an anderer Stelle im Dokument oder eine auszuführende Aktion dar."
type: docs
weight: 390
url: /de/python-net/aspose.pdf.annotations/linkannotation/
---

## LinkAnnotation class

Stellt entweder einen Hypertext‑Link zu einem Ziel an anderer Stelle im Dokument oder eine auszuführende Aktion dar.

Der Typ LinkAnnotation stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| LinkAnnotation(page, rect) | Initialisiert eine neue Instanz der Klasse LinkAnnotation |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| vertical_alignment | Liest oder setzt die vertikale Ausrichtung eines Absatzes |
| horizontal_alignment | Liest oder setzt die Textausrichtung für die Anmerkung. |
| Rand | Liest oder setzt einen äußeren Rand für den Absatz (für die PDF-Erstellung) |
| is_first_paragraph_in_column | Liest oder setzt einen Bool-Wert, der angibt, ob dieser Absatz in die nächste Spalte gesetzt wird.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_kept_with_next | Liest oder setzt einen Bool-Wert, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_in_new_page | Liest oder setzt einen Bool-Wert, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_in_line_paragraph | Liest oder setzt, ob ein Absatz inline ist.<br/>            Standard ist false. (für die PDF-Erstellung) |
| Hyperlink | Liest oder setzt den Fragment-Hyperlink (für den PDF-Generator). |
| z_index | Liest oder setzt einen int‑Wert, der die Z‑Reihenfolge des Diagramms angibt. Ein Diagramm mit größerem ZIndex <br/>            wird über dem Diagramm mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Diagramm mit negativem <br/>            ZIndex wird hinter dem Text auf der Seite platziert. |
| aktualisiere_erscheinung_beim_konvertieren | Wenn true, wird das Aussehen der Anmerkung aktualisiert, bevor das PF-Dokument in ein Bild konvertiert wird. Dies ermöglicht eine korrekte Konvertierung der Felder, kann jedoch wahrscheinlich mehr Zeit benötigen. |
| verwende_schriftart_teilmenge | Wenn diese Eigenschaft auf true gesetzt ist, werden Schriftarten dem Dokument als Teilmengen hinzugefügt. Der Standardwert ist true. |
| flaggen | Flags der Anmerkung. |
| anmerkung_typ | Ermittelt den Typ der Anmerkung. |
| breite | Liest oder setzt die Breite der Anmerkung. |
| aktionen | Liest die Liste der Annotationsaktionen. |
| höhe | Liest oder setzt die Höhe der Anmerkung. |
| rechteck | Liest oder setzt das Annotationsrechteck. |
| inhalt | Liest oder setzt den Anmerkungstext. |
| Name | Liest oder setzt den Anmerkungsnamen auf der Seite. |
| geändert | Liest oder setzt Datum und Uhrzeit, wann die Anmerkung zuletzt geändert wurde. |
| farbe | Liest oder setzt die Anmerkungsfarbe. |
| border | Liest oder setzt die Randmerkmale der Anmerkung. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| aktiver_zustand | Liest oder setzt den aktuellen Annotationsanzeigestatus. |
| eigenschaften | Liest die Anmerkungsmerkmale. |
| zustände | Liest das Erscheinungsdictionary der Anmerkung. |
| ausrichtung | Anmerkungs-Ausrichtung. Diese Eigenschaft ist veraltet. Verwenden Sie stattdessen HorizontalAligment. |
| text_horizontale_ausrichtung | Liest oder setzt die Textausrichtung für die Anmerkung. |
| vollständiger_name | Ermittelt den vollständig qualifizierten Namen der Anmerkung. |
| erscheinung | Ermittelt das Erscheinungsdictionary der Anmerkung. |
| seiten_index | Liest den Index der Seite, die die Annotation enthält. |
| action | Eine Aktion, die ausgeführt wird, wenn die Linkannotation aktiviert wird. |
| destination | Ein Ziel, das angezeigt wird, wenn die Annotation aktiviert wird. |
| Hervorhebung | Der visuelle Effekt, der verwendet wird, wenn die Maustaste im aktiven Bereich gedrückt oder gehalten wird. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Klonen dieser Instanz.<br/>            Virtuelle Methode. Gibt immer null zurück. |
| get_rectangle(consider_rotation) | Gibt das Rechteck der Anmerkung zurück, wobei die Seitenrotation berücksichtigt wird. |
| accept(visitor) | Akzeptiert ein Besucherobjekt, um die Anmerkung zu verarbeiten. |
| flatten() | Platziert Annotationsinhalte direkt auf der Seite,<br/>            das Annotationsobjekt wird entfernt. |
| change_after_resize(transform) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |

### Siehe auch

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

