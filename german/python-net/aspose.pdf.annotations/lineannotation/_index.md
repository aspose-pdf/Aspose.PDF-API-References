---
title: "LineAnnotation"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die eine Linien‑Annotation darstellt."
type: docs
weight: 380
url: /de/python-net/aspose.pdf.annotations/lineannotation/
---

## LineAnnotation class

Klasse, die eine Linien‑Annotation darstellt.

Der Typ LineAnnotation stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| LineAnnotation(document, start, end) | Initialisiert eine neue Instanz der Klasse LineAnnotation |
| LineAnnotation(page, rect, start, end) | Initialisiert eine neue Instanz der Klasse LineAnnotation |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| vertical_alignment | Keine |
| horizontal_alignment | Liest oder setzt die Textausrichtung für die Anmerkung. |
| Rand | Keine |
| is_first_paragraph_in_column | Keine |
| is_kept_with_next | Keine |
| is_in_new_page | Keine |
| is_in_line_paragraph | Keine |
| Hyperlink | Keine |
| z_index | Keine |
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
| title | Liest oder setzt einen Text, der in der Titelleiste der Anmerkung angezeigt wird. |
| rich_text | Liest oder setzt eine Rich-Text-Zeichenfolge, die im Popup-Fenster angezeigt wird, wenn die Anmerkung geöffnet wird. |
| creation_date | Liefert Datum und Uhrzeit, wann die Anmerkung erstellt wurde. |
| subject | Liefert Text, der die Beschreibung des Objekts darstellt. |
| popup | Popup-Anmerkung zum Eingeben oder Bearbeiten des mit dieser Anmerkung verknüpften Textes. |
| opacity | Liest oder setzt den konstanten Deckkraftwert, der beim Rendern der Anmerkung verwendet wird. |
| in_reply_to | Ein Verweis auf die Anmerkung, auf die diese Anmerkung "antwortet".<br/>            Beide Anmerkungen müssen sich auf derselben Seite des Dokuments befinden. |
| reply_type | Eine Zeichenkette, die die Beziehung (den "Antworttyp") zwischen dieser Anmerkung<br/>            und einer durch InReplyTo angegebenen spezifiziert. |
| starting | Liest oder setzt den Startpunkt der Linie. |
| starting_style | Liest oder setzt den Endstil der Linie für den Startpunkt. |
| ending | Liest oder setzt den Endpunkt der Linie. |
| ending_style | Liest oder setzt den Endstil für den Endpunkt der Linie. |
| interior_color | Liest oder setzt die Innenfarbe der Anmerkung. |
| leader_line | Liest oder setzt die Länge der leader line. |
| leader_line_extension | Liest oder setzt die Länge der Führungsleitungserweiterung. |
| show_caption | Liest oder setzt das boolesche Flag, das bestimmt, ob Inhalte als Beschriftung angezeigt werden müssen. |
| leader_line_offset | Liest oder setzt den Versatz der Führungsleitung. |
| caption_offset | Liest oder setzt den Textversatz der Beschriftung von ihrer normalen Position. |
| caption_position | Liest oder setzt die Position der Anmerkungsbeschriftung. |
| measure | Messgrößen, die für diese Anmerkung angegeben sind. |
| intent | Liest oder setzt die Absicht der Linienannotation. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Keine |
| get_rectangle(consider_rotation) | Gibt das Rechteck der Anmerkung zurück, wobei die Seitenrotation berücksichtigt wird. |
| accept(visitor) | Akzeptiert Besucher zur Anmerkungsverarbeitung. |
| flatten() | Platziert Annotationsinhalte direkt auf der Seite,<br/>            das Annotationsobjekt wird entfernt. |
| change_after_resize(transform) | Aktualisiert die Start‑ und Endpunkte gemäß der Matrixtransformation. |

### Siehe auch

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

