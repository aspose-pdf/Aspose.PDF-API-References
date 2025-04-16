---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes Enum. Konvertierte PDFs können Rasterbilder enthalten. Dieses Enum definiert Methoden, wie Rasterbilder während der Konvertierung von PDF zu HTML behandelt werden können.
type: docs
weight: 5720
url: /de/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes Enumeration

Konvertierte PDFs können Rasterbilder (.png, *.jpeg usw.) enthalten. Dieses Enum definiert Methoden, wie Rasterbilder während der Konvertierung von PDF zu HTML behandelt werden können.

```csharp
public enum RasterImagesSavingModes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | Für jede unterschiedliche Rasterdatei wird ein Wrapper-SVG-Bild generiert, und das Rasterbild wird als Base64-kodierte Zeichenfolgen in dieses SVG-Bild eingebettet. |
| AsExternalPngFilesReferencedViaSvg | `1` | Unterschiedliche Rasterbilder werden als PNG-Dateien getrennt gespeichert, aber über umschließende SVG-Bilder referenziert, d.h. es wird eine PNG-Datei und ein SVG für jedes Rasterbild generiert, und jedes dieser SVGs enthält Links zur entsprechenden PNG-Datei. |
| AsEmbeddedPartsOfPngPageBackground | `2` | Es wird eine große PNG-Hintergrunddatei für jede Ergebnisseite generiert. Rasterbilder werden in diese Datei eingebettet und als Bereiche dieses Bildes gerendert. Es werden keine externen PNG-Dateien für jedes Bild generiert, nur eine PNG-Datei pro Seite wird im Konvertierungsergebnis vorhanden sein. |
| DontSave | `3` | Bilder für Fixed Layout nicht speichern. |

### Siehe auch

* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)