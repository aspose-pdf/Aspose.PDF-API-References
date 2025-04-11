---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImage-Klasse. Klasse, die das Bild-X-Objekt darstellt
type: docs
weight: 11350
url: /de/net/aspose.pdf/ximage/
---
## XImage-Klasse

Klasse, die das Bild-X-Objekt darstellt.

```csharp
public sealed class XImage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Wenn das Bild Transparenz enthält, gibt es true zurück; andernfalls false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Gibt den Bildfiltertyp zurück. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Gibt die graustufige Version des Bildes zurück. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Gibt die Höhe des Bildes zurück. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Gibt ein Flag zurück, das angibt, ob das Bild als Bildmaske behandelt werden soll (siehe 8.9.6, "Maskierte Bilder"). Wenn dieses Flag true ist, muss der Wert von BitsPerComponent 1 sein und Mask und ColorSpace dürfen nicht angegeben werden; unmaskierte Bereiche werden mit der aktuellen nicht-streichenden Farbe gemalt. Standardwert: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadaten des Bildes. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Gibt den Bildnamen zurück oder setzt ihn. Bitte beachten Sie, dass, wenn Sie den Namen des Bildes ändern, das in den Seiteninhalten Referenzen hat, das Dokument möglicherweise inkorrekt wird. Bitte verwenden Sie in diesem Fall die Methode XImage.Rename. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Gibt die Breite des Bildes zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Fügt der XImage eine Stanzmaske hinzu. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Gibt den Farbtyp des Bildes zurück. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Gibt den Namen des Bildes in seiner Sammlung zurück. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Ruft die Rohbilddaten aus dem Quellbild ab. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Gibt true zurück, wenn beide Bilder auf dasselbe Objekt verweisen. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Benennt das Bild um und ersetzt alle Referenzen auf das Bild mit dem neuen Namen |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Speichert die Bilddaten in den Stream als JPEG-Bild. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Speichert das Bild im Stream im angeforderten Format. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Speichert die Bilddaten in den Stream als JPEG-Bild mit der angegebenen Auflösung. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Speichert das Bild im Stream im angeforderten Format mit der angegebenen Auflösung. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Gibt den ursprünglichen Bildstream zurück. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)