---
title: "InkAnnotation"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt ein freihändiges „Kritzel“ dar, das aus einem oder mehreren getrennten Pfaden besteht."
type: docs
weight: 350
url: /de/python-net/aspose.pdf.annotations/inkannotation/
---

## InkAnnotation class

Stellt ein freihändiges „Kritzel“ dar, das aus einem oder mehreren getrennten Pfaden besteht.

Der InkAnnotation‑Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| InkAnnotation(document, ink_list) | Initialisiert eine neue Instanz der InkAnnotation‑Klasse |
| InkAnnotation(page, rect, ink_list) | Initialisiert eine neue Instanz der InkAnnotation‑Klasse |
| InkAnnotation(page, rect, ink_list) | Initialisiert eine neue Instanz der InkAnnotation‑Klasse |
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
| cap_style | Stil der Linienenden der Tintenanmerkung. |
| ink_list | Liest oder setzt die Liste von Gesten, die unabhängige Linien darstellen und durch Point[]‑Arrays repräsentiert werden. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Keine |
| get_rectangle(consider_rotation) | Gibt das Rechteck der Anmerkung zurück, wobei die Seitenrotation berücksichtigt wird. |
| accept(visitor) | Akzeptiert ein Besucherobjekt, um die Anmerkung zu verarbeiten. |
| flatten() | Platziert Annotationsinhalte direkt auf der Seite,<br/>            das Annotationsobjekt wird entfernt. |
| change_after_resize(transform) | Aktualisiert die Punkte in InkList gemäß der Matrixtransformation. |

### Siehe auch

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

