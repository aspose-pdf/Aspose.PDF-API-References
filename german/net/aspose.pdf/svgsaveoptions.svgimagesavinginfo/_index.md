---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo-Klasse. Diese Klasse stellt eine Menge von Daten dar, die mit dem Speichern von externen Ressourcenbilddateien während der PDF-zu-HTML-Konvertierung verbunden sind.
type: docs
weight: 10260
url: /de/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo-Klasse

Diese Klasse stellt eine Menge von Daten dar, die mit dem Speichern von externen Ressourcenbilddateien während der PDF-zu-HTML-Konvertierung verbunden sind.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Vom Konverter gesetzt. Vorgeschlagener Dateiname, der vom Konverter an den Code der benutzerdefinierten Methode übergeben wird. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie die Datei verarbeitet oder wo sie gespeichert werden soll. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Vom Konverter gesetzt. Stellt den binären Inhalt der gespeicherten Datei dar. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn aus bestimmten Gründen die vorgeschlagene Datei nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters selbst auf die Standardweise des Konverters verarbeitet werden soll. Das Setzen auf true bedeutet, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst behandeln muss (in beiden Sinne - zum Speichern irgendwo und zum Benennen in der referenzierten Datei). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | Stellt den Typ des gespeicherten Bildes dar, das in HTML referenziert wird. Vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was getan werden soll. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Vom Konverter gesetzt. Vorgeschlagener Dateiname, der vom Konverter an den Code der benutzerdefinierten Methode übergeben wird. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie die Datei verarbeitet oder wo sie gespeichert werden soll. |

### Siehe auch

* Klasse [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* Klasse [SvgSaveOptions](../svgsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)