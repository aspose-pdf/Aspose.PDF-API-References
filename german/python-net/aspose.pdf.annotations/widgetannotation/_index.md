---
title: "WidgetAnnotation"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die eine Widget-Annotation repräsentiert."
type: docs
weight: 870
url: /de/python-net/aspose.pdf.annotations/widgetannotation/
---

## WidgetAnnotation class

Klasse, die eine Widget-Annotation repräsentiert.

Der WidgetAnnotation-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| WidgetAnnotation(doc) | Initialisiert eine neue Instanz der WidgetAnnotation-Klasse |
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
| aktionen | Ermittelt die Anmerkungsaktionen. |
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
| bei_aktivierung | Eine Aktion, die ausgeführt werden soll, wenn die Anmerkung aktiviert wird. |
| Hervorhebung | Modus für Anmerkungs-Hervorhebung. |
| Eltern | Liefert den Elternteil der Anmerkung. |
| default_appearance | Liefert oder setzt das Standardaussehen des Feldes. |
| read_only | Liefert oder setzt den Nur-Lese-Status des Feldes. |
| required | Liefert oder setzt den Pflichtstatus des Feldes. |
| exportable | Liefert oder setzt das exportierbare Flag des Feldes. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Klonen dieser Instanz.<br/>            Virtuelle Methode. Gibt immer null zurück. |
| get_rectangle(consider_rotation) | Gibt das Rechteck der Anmerkung zurück, wobei die Seitenrotation berücksichtigt wird. |
| accept(visitor) | Akzeptiert Besucher. |
| flatten() | Platziert Annotationsinhalte direkt auf der Seite,<br/>            das Annotationsobjekt wird entfernt. |
| change_after_resize(transform) | Aktualisiert Parameter und Erscheinungsbild gemäß der Matrixtransformation. |

### Siehe auch

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

