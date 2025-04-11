---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo-Klasse. Diese Klasse stellt eine Menge von Daten dar, die mit dem Speichern von externen Ressourcenbilddateien während der PDF-zu-HTML-Konvertierung verbunden sind.
type: docs
weight: 5640
url: /de/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo-Klasse

Diese Klasse stellt eine Menge von Daten dar, die mit dem Speichern von externen Ressourcenbilddateien während der PDF-zu-HTML-Konvertierung verbunden sind.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Vom Konverter festgelegt. Vorgeschlagener Dateiname, der vom Konverter an den Code der benutzerdefinierten Methode übergeben wird. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie die Datei verarbeitet oder wo sie gespeichert werden soll. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Vom Konverter festgelegt. Stellt den binären Inhalt der gespeicherten Datei dar. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn aus bestimmten Gründen die vorgeschlagene Datei nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters selbst auf die Standardweise des Konverters verarbeitet werden soll. Das Setzen auf true bedeutet, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst behandeln muss (in beiden Sinne - zum Speichern irgendwo und zum Benennen in der referenzierenden Datei). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Teilt dem benutzerdefinierten Code mit, zu welcher Seite des generierten Satzes von HTML-Seitendateien das gespeicherte Bild gehört. Wenn das Aufteilen in Seiten deaktiviert ist, enthält dieser Wert immer '1', da in diesem Fall nur eine HTML-Seite generiert wird. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Stellt den Typ des in HTML referenzierten gespeicherten Bildes dar. Vom Konverter festgelegt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was zu tun ist. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | Das gespeicherte Bild kann zu HTML selbst gehören oder aus SVG extrahiert werden, das in HTML eingebettet ist. Diese Eigenschaft kann dem benutzerdefinierten Code mitteilen, welcher Typ von Elternteil des verarbeiteten Bildes vorliegt. Sie wird vom Konverter festgelegt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was mit diesem Bild geschehen soll (z. B. kann der benutzerdefinierte Code entscheiden, wo das Bild gespeichert werden soll oder wie es im Inhalt des Elternteils referenziert werden muss). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Teilt dem benutzerdefinierten Code mit, zu welcher Seite des ursprünglichen PDF-Dokuments das gespeicherte Bild gehört. Da es möglich ist, dass nicht alle Seiten des ursprünglichen Dokuments gespeichert werden, gibt dieser Wert die Host-Seitennummer im ursprünglichen PDF an. Wenn die ursprüngliche Seitennummer aus irgendeinem Grund unbekannt ist, wird immer '1' zurückgegeben. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Vom Konverter festgelegt. Vorgeschlagener Dateiname, der vom Konverter an den Code der benutzerdefinierten Methode übergeben wird. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie die Datei verarbeitet oder wo sie gespeichert werden soll. |

### Siehe auch

* Klasse [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)