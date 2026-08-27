---
title: "Überschrift"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Überschrift dar."
type: docs
weight: 460
url: /de/python-net/aspose.pdf/heading/
---

## Heading class

Stellt eine Überschrift dar.

Der Typ Überschrift stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Überschrift(level) | Initialisiert eine neue Instanz der Klasse Überschrift |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| vertical_alignment | Liest oder setzt die vertikale Ausrichtung des TextFragments. |
| horizontal_alignment | Liest oder setzt die horizontale Ausrichtung des TextFragments. |
| Rand | Liest oder setzt einen äußeren Rand für den Absatz (für die PDF-Erstellung) |
| is_first_paragraph_in_column | Liest oder setzt einen Bool-Wert, der angibt, ob dieser Absatz in die nächste Spalte gesetzt wird.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_kept_with_next | Liest oder setzt einen Bool-Wert, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_in_new_page | Liest oder setzt einen Bool-Wert, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_in_line_paragraph | Liest oder setzt, ob ein Absatz inline ist.<br/>            Standard ist false. (für die PDF-Erstellung) |
| Hyperlink | Setzt den Hyperlink des Fragments. |
| z_index | Liest oder setzt einen int‑Wert, der die Z‑Reihenfolge des Diagramms angibt. Ein Diagramm mit größerem ZIndex <br/>            wird über dem Diagramm mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Diagramm mit negativem <br/>            ZIndex wird hinter dem Text auf der Seite platziert. |
| replace_options | Liest die Optionen zum Ersetzen von Text. Die Optionen definieren das Verhalten, wenn der Fragmenttext kürzer oder länger ersetzt wird. |
| text | Liest oder setzt das Zeichenketten-Textobjekt, das das [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) Objekt darstellt. |
| text_state | Liest oder setzt den Textzustand für den Text, den das [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) Objekt darstellt. |
| segments | Liest Textsegmente für das aktuelle [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| position | Liest oder setzt die Textposition für den Text, dargestellt mit dem [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) Objekt. |
| baseline_position | Liest die Textposition für den Text, dargestellt mit dem [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) Objekt.<br/>            Der YIndent der Position-Struktur stellt die Grundlinienkoordinate des TextFragments dar. |
| Rechteck | Liest das Rechteck des TextFragments |
| page | Liest die Seite, die das TextFragment enthält. |
| Formular | Liest das Formularobjekt, das das TextFragment enthält. |
| wrap_lines_count | Liest oder setzt die Zeilenumbruchanzahl für diesen Absatz (nur für PDF-Erstellung). |
| end_note | Liest oder setzt die Absatz-Endnotiz.(nur für PDF-Erstellung) |
| foot_note | Liest oder setzt die Absatzfußnote.(nur für PDF-Erstellung) |
| toc_page | Gibt die Seite zurück, die diese Überschrift enthält. |
| top | Gibt das obere Y dieser Überschriften zurück. |
| start_number | Gibt die Startnummer der Überschrift zurück. |
| is_auto_sequence | Gibt zurück, ob die Überschrift automatisch nummeriert werden soll. |
| is_in_list | Gibt zurück, ob die Überschrift in der Inhaltsliste sein soll. |
| destination_page | Gibt die Zielseite zurück. |
| level | Gibt die Ebene zurück. |
| style | Liest oder setzt den Stil. |
| user_label | Liest oder setzt das Benutzerlabel. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Kopiert die Überschrift. |
| isolate_text_segments(start_index, length) | Liest [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s), die den angegebenen Teil des [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) Textes darstellen. |
| clone_with_segments() | Kopiert die Überschrift mit allen Segmenten. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

