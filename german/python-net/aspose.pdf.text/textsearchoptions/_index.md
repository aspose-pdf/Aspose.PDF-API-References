---
title: "TextSearchOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt Textsuchoptionen dar"
type: docs
weight: 460
url: /de/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Stellt Textsuchoptionen dar

Der Typ TextSearchOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | Initialisiert eine neue Instanz der Klasse TextSearchOptions |
| TextSearchOptions(rectangle) | Initialisiert eine neue Instanz der Klasse TextSearchOptions |
| TextSearchOptions(rectangle, is_regular_expression_used) | Initialisiert eine neue Instanz der Klasse TextSearchOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| is_regular_expression_used | Ruft ab oder legt fest, ob ein regulärer Ausdruck verwendet wird. |
| limit_to_page_bounds | Ruft ab oder legt fest, dass Text innerhalb der Seitenbegrenzungen gesucht wird. |
| Rechteck | Ruft ab oder legt das Rechteck fest, das den gesuchten Text begrenzt. |
| use_font_engine_encoding | Ruft ab oder legt fest, dass Text mit der Schriftengine-Kodierung gesucht wird.<br/>            true - bedeutet, dass die Schriftengine-Kodierung verwendet wird (versuchen Sie dies, wenn die Textsuche aufgrund unvollständiger Kodierung im Dokument fehlschlägt)<br/>            false - bedeutet, dass die Dokumentschriftkodierung verwendet wird (Standardwert) |
| ignore_shadow_text | Ruft ab oder legt fest, dass Textfragmente, die den Schatten von normalem Text darstellen, während der Suche ignoriert werden.<br/>            true - bedeutet, dass Schatten-Text nicht gefunden wird (versuchen Sie dies, wenn die Textsuche duplizierte Fragmente an nahen Positionen zurückgibt)<br/>            false - bedeutet, dass Schatten-Text ebenso wie normaler Text gefunden wird (Standardwert) |
| log_text_extraction_errors | Ruft ab oder legt fest, dass Fehler bei der Textextraktion (Dekodierung) im Text‑ (Fragment‑)Absorber protokolliert werden.<br/>            true - bedeutet, dass Fehler bei der Textextraktion (Dekodierung) protokolliert werden. Dies kann die Leistung verringern.<br/>            false (Standard) - keine Fehlerprotokollierung. |
| ignore_resource_font_errors | Ruft ab oder legt fest, dass Fehler im Zusammenhang mit fehlenden Schriftarten vom Text‑ (Fragment‑)Absorber ignoriert werden.<br/>            true - bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen.<br/>            false (Standard) - ein Fehler wegen fehlender Schriftart beendet die Verarbeitung durch Auslösen einer Ausnahme. |
| search_for_text_related_graphics | Ruft ab oder legt den Wert fest, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) während der Textsuche ermöglicht.<br/>            true - die Suche nach textbezogenen Grafiken wird durchgeführt (Standardwert).<br/>            false - grafische Elemente, die im Quelldokument vorhanden sein können, werden ignoriert. Verwenden Sie dies bei Leistungsproblemen oder wenn keine Unterstreichungen, Hintergründe oder Beschneidungen verarbeitet werden müssen. |
| stored_graphic_elements_max_count | Ruft ab oder legt den Wert fest, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) auf einer Seite auf die angegebene Anzahl von Elementen begrenzt.<br/>            Der Standardwert ist 250. Verwenden Sie bei Leistungsproblemen einen kleineren Wert, bei fehlenden Grafikelementen einen größeren Wert. |
| search_in_annotations | Ruft ab oder legt den Wert fest, der die Suche nach Text in Anmerkungen ermöglicht.<br/>            true - Text wird in Anmerkungen gesucht.<br/>            false - Text in Anmerkungen wird nicht vom TextFragmentAbsorber geparst. |

### Siehe auch

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

