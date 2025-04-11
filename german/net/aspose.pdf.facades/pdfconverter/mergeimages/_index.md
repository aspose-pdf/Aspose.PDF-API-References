---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter-Methode. Führt eine Liste von Bildstreams zu einem Bildstream zusammen. Png/jpg/tiff-Ausgabeformate werden unterstützt, falls ein nicht unterstützter Format-Ausgabestream standardmäßig als Jpeg kodiert wird.
type: docs
weight: 180
url: /de/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages-Methode

Führt eine Liste von Bildstreams zu einem Bildstream zusammen. Png/jpg/tiff-Ausgabeformate werden unterstützt, falls ein nicht unterstützter Format-Ausgabestream standardmäßig als Jpeg kodiert wird.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputImagesStreams | List`1 | Die Liste der Bildstreams, die zusammengeführt werden sollen. |
| outputImageFormat | ImageFormat | Bildausgabeformat für den zusammengeführten Stream. |
| mergeMode | ImageMergeMode | Zusammenführungsmodus. Wird für Png/Jpg-Formate verwendet. |
| horizontal | Nullable`1 | Horizontaler Anteil zur Festlegung der Canvas-Breite für den Ausgabebildstream. Wird nur für Png/Jpg-Formate mit ImageMergeMode.Center verwendet. |
| vertical | Nullable`1 | Vertikaler Anteil zur Festlegung der Canvas-Höhe für den Ausgabebildstream. Wird nur für Png/Jpg-Formate mit ImageMergeMode.Center verwendet. |

### Rückgabewert

Bildstream, kodiert im Ausgabebildformat.

### Siehe auch

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)