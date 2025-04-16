---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo-Klasse. Wenn die SplitToPages-Eigenschaft von HtmlSaveOptions gesetzt ist, werden während der Konvertierung von PDF zu HTML mehrere HTML-Dateien erstellt. Diese Klasse stellt eine Menge von Daten dar, die mit dem benutzerdefinierten Speichern des Markups einer HTML-Seite während der Konvertierung von PDF zu HTML verbunden sind.
type: docs
weight: 5670
url: /de/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## Klasse HtmlSaveOptions.HtmlPageMarkupSavingInfo

Wenn die SplitToPages-Eigenschaft von HtmlSaveOptions gesetzt ist, werden während der Konvertierung von PDF zu HTML mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Klasse stellt eine Menge von Daten dar, die mit dem benutzerdefinierten Speichern des Markups einer HTML-Seite während der Konvertierung von PDF zu HTML verbunden sind.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Felder

| Name | Beschreibung |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Vom Konverter gesetzt. Stellt das gespeicherte HTML als Stream dar |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Sollte im benutzerdefinierten Code gesetzt werden, wenn nötig. Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn aus bestimmten Gründen das bereitgestellte HTML-Markup nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters selbst auf die Standardweise des Konverters verarbeitet werden soll. Das Setzen dieses Flags im benutzerdefinierten Code bedeutet, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter dies selbst übernehmen muss. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Vom Konverter gesetzt. Wenn die SplitToPages-Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft enthält die Ordinalzahl der gespeicherten HTML-Seite. Die Eigenschaft kann in der Logik des benutzerdefinierten Codes verwendet werden, um zu entscheiden, wie die HTML-Seite verarbeitet oder wo sie gespeichert werden soll. Wenn das Aufteilen in Seiten deaktiviert ist, enthält dieser Wert immer '1', da in diesem Fall nur eine große HTML-Seite für das gesamte Quell-Dokument generiert wird. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Vom Konverter gesetzt. Wenn die SplitToPages-Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft informiert den benutzerdefinierten Code, von welcher Seite des ursprünglichen PDFs das gespeicherte HTML-Markup erstellt wurde. Wenn die ursprüngliche Seitennummer aus irgendeinem Grund unbekannt ist oder SplitOnPages=false ist, enthält diese Eigenschaft immer '0', was signalisiert, dass der Konverter die genaue ursprüngliche PDF-Seitennummer für die bereitgestellte HTML-Markup-Datei nicht liefern kann. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Vom Konverter gesetzt. Angenommener Dateiname, der vom Konverter an den Code der benutzerdefinierten Methode übergeben wird. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie der Inhalt verarbeitet oder wo er gespeichert werden soll. |

### Siehe auch

* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)