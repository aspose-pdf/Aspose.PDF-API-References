---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ImagesDifference-Klasse. Stellt die Ergebnis-Klasse zum Vergleichen von zwei PDF-Seiten dar
type: docs
weight: 3230
url: /de/net/aspose.pdf.comparison/imagesdifference/
---
## Klasse ImagesDifference

Stellt die Ergebnis-Klasse zum Vergleichen von zwei PDF-Seiten dar.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Gibt das Differenzarray zurück. Dieses Array ähnelt dem ursprünglichen Bilddatenarray, das als Ergebnis der LockBits-Methode erhalten wurde. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | Die Höhe der Differenz. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Gibt das Bild der ersten verglichenen Seite zurück. Das Bild hat ein Pixel-Format von 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Der Stride der Bilddaten der Differenz. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Konvertiert das Differenzarray in ein Bitmap-Bild unter Verwendung der angegebenen Farben. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Führt alle notwendigen Aufräumoperationen durch, bevor das Objekt zerstört wird. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Gibt ein neues Bitmap zurück, das das Zielbild darstellt, indem das Differenzarray auf das Quellbild angewendet wird. |

### Siehe auch

* Namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../)