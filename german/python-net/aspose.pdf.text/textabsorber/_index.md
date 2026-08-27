---
title: "TextAbsorber"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt ein Absorber‑Objekt für Text dar.<br/>            Führt die Textextraktion durch und bietet Zugriff auf das Ergebnis über das [text](/pdf/python-net/aspose.pdf.text/textabsorber/)‑Objekt."
type: docs
weight: 320
url: /de/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Stellt ein Absorber‑Objekt für Text dar.<br/>            Führt die Textextraktion durch und bietet Zugriff auf das Ergebnis über das [text](/pdf/python-net/aspose.pdf.text/textabsorber/)‑Objekt.

Der TextAbsorber-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| TextAbsorber() | Initialisiert eine neue Instanz von [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | Initialisiert eine neue Instanz der TextAbsorber-Klasse |
| TextAbsorber(extraction_options, text_search_options) | Initialisiert eine neue Instanz der TextAbsorber-Klasse |
| TextAbsorber(text_search_options) | Initialisiert eine neue Instanz der TextAbsorber-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| text | Gibt den extrahierten Text zurück, den der [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) aus dem PDF‑Dokument oder der Seite extrahiert. |
| has_errors | Der Wert gibt an, ob bei der Textextraktion Fehler gefunden wurden.<br/>Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern. |
| errors | Liste von [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/)-Objekten. Sie enthält Informationen über während der Textextraktion gefundene Fehler.<br/>Die Fehlersuche wird nur durchgeführt, wenn TextSearchOptions.LogTextExtractionErrors = true; und sie kann die Leistung verringern. |
| extraction_options | Liest oder setzt Optionen für die Textextraktion. |
| text_search_options | Liest oder setzt Textsuchoptionen. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| visit(page) | Extrahiert Text auf der angegebenen Seite |
| visit(form) | Extrahiert Text im angegebenen XForm. |
| visit(pdf) | Extrahiert Text im angegebenen Dokument |

### Siehe auch

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

