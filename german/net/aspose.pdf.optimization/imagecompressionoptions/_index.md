---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.ImageCompressionOptions-Klasse. Die Klasse enthält Optionen für die Bildkompression
type: docs
weight: 7950
url: /de/net/aspose.pdf.optimization/imagecompressionoptions/
---
## Klasse ImageCompressionOptions

Die Klasse enthält Optionen für die Bildkompression.

```csharp
public class ImageCompressionOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Wenn dieses Flag auf true gesetzt ist, werden die Bilder im Dokument komprimiert. Der Kompressionsgrad wird mit der Eigenschaft ImageQuality angegeben. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Ruft die Kodierung ab oder setzt sie, die zum Speichern von Bildern verwendet wird. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Gibt den Grad der Bildkompression an, wenn das CompressImages-Flag verwendet wird. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Gibt die maximale Auflösung der Bilder an. Wenn das Bild eine höhere Auflösung hat, wird es skaliert. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Wenn dieses Flag auf true gesetzt ist und CompressImages true ist, werden die Bilder verkleinert, wenn die Bildauflösung größer ist als der angegebene MaxResolution-Parameter. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Version des Kompressionsalgorithmus. Mögliche Werte sind: 1. Standardkompression, 2. Schnell (verbesserte Kompression, die schneller als die Standardkompression ist, aber möglicherweise nicht für alle Bilder anwendbar ist), 3. Gemischt (Standardkompression wird auf Bilder angewendet, die nicht mit dem schnelleren Algorithmus komprimiert werden können, dies kann die beste Kompression bieten, ist aber langsamer als der "schnelle" Algorithmus. Die Version "Schnell" ist nicht anwendbar für die Größenänderung von Bildern (es wird die Standardmethode verwendet). Standard ist "Standard". |

### Siehe auch

* Namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* Assembly [Aspose.PDF](../../)