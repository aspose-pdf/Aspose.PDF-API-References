---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter-metod. Slår samman lista av bildströmmar som en bildström. Png/jpg/tiff utdataformat stöds i fall av att använda icke stödd formatutdataström som kodas som Jpeg som standard
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages metod

Slår samman lista av bildströmmar som en bildström. Png/jpg/tiff utdataformat stöds, i fall av att använda icke stödd formatutdataström som kodas som Jpeg som standard.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputImagesStreams | List`1 | Listan av bildströmmar att slå samman. |
| outputImageFormat | ImageFormat | Bildutdataformat för den sammanslagna strömmen. |
| mergeMode | ImageMergeMode | Sammanfogningsläge. Används för Png/Jpg-format. |
| horizontal | Nullable`1 | Horisontell förhållande för att ställa in dukbredd för utdata bildström. Används för Png/Jpg-format med ImageMergeMode.Center endast. |
| vertical | Nullable`1 | Vertikal förhållande för att ställa in dukhöjd för utdata bildström. Används för Png/Jpg-format med ImageMergeMode.Center endast. |

### Returvärde

Bildström kodad som utdata bildformat.

### Se Även

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)