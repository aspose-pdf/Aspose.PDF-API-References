---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt ein Absorber‑Objekt für Textfragmente dar.<br/>            Führt die Textsuche durch und bietet Zugriff auf die Suchergebnisse über die [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)‑Sammlung."
type: docs
weight: 400
url: /de/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Stellt ein Absorber‑Objekt für Textfragmente dar.<br/>            Führt die Textsuche durch und bietet Zugriff auf die Suchergebnisse über die [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)‑Sammlung.

Der Typ TextFragmentAbsorber stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| TextFragmentAbsorber() | Initialisiert eine neue Instanz des [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/), die die Suche aller Textsegmente des Dokuments oder der Seite durchführt. |
| TextFragmentAbsorber(text_edit_options) | Initialisiert eine neue Instanz der Klasse TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | Initialisiert eine neue Instanz der Klasse TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | Initialisiert eine neue Instanz der Klasse TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | Initialisiert eine neue Instanz der Klasse TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | Initialisiert eine neue Instanz der Klasse TextFragmentAbsorber |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| text | Gibt den extrahierten Text zurück, den der [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) aus dem PDF‑Dokument oder der Seite extrahiert. |
| has_errors | Der Wert gibt an, ob bei der Textextraktion Fehler gefunden wurden.<br/>Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern. |
| errors | Liste von [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/)-Objekten. Sie enthält Informationen über während der Textextraktion gefundene Fehler.<br/>Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern. |
| extraction_options | Liest oder setzt Optionen für die Textextraktion. |
| text_search_options | Liest oder setzt Suchoptionen. Die Optionen ermöglichen die Suche mit regulären Ausdrücken. |
| text_fragments | Liest die Sammlung von Suchvorkommen, die mit [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/)-Objekten dargestellt werden. |
| phrase | Liest oder setzt die Phrase, nach der der [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) im PDF‑Dokument oder auf der Seite sucht. |
| text_edit_options | Liest oder setzt Textbearbeitungsoptionen. Die Optionen definieren ein spezielles Verhalten, wenn das gewünschte Symbol nicht mit der Schriftart dargestellt werden kann. |
| text_replace_options | Liest oder setzt Optionen zum Ersetzen von Text. Die Optionen definieren das Verhalten, wenn Fragmenttext kürzer oder länger ersetzt wird. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| visit(page) | Führt eine Suche auf der angegebenen Seite aus. |
| visit(pdf) | Führt eine Suche im angegebenen Dokument aus. |
| visit(x_form) | Führt eine Suche im angegebenen Form-Objekt aus. |
| apply_for_all_fragments(font) | Wendet die font für alle Textfragmente an, die absorbiert wurden. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| apply_for_all_fragments(font_size) | Wendet die font size für alle Textfragmente an, die absorbiert wurden. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| apply_for_all_fragments(font, font_size) | Wendet font und size für alle Textfragmente an, die absorbiert wurden. Es ist schneller als das Durchlaufen der Fragmente, wenn alle Fragmente auf den Seite(n) absorbiert wurden. Andernfalls funktioniert es ähnlich wie beim Durchlaufen. |
| remove_all_text(page) | Entfernt allen Text von der angegebenen Seite. |
| remove_all_text(page, rect) | Entfernt Text innerhalb des angegebenen Rechtecks von der angegebenen Seite. |
| remove_all_text(document) | Entfernt allen Text aus dem Dokument. |
| reset() | Löscht die TextFragments-Sammlung dieses [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) Objekts. |

### Siehe auch

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

