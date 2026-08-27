---
title: "PdfConverter.MergeImages"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfConverter-metod. Slår samman en lista med bildströmmar till en enda bildström. PNG/JPG/TIFF-utdataformat stöds, men om ett icke‑stödd format används kodas utdataflödet som JPEG som standard."
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

Slår samman en lista med bildströmmar till en enda bildström. Png/jpg/tiff-utdataformat stöds, och om ett icke‑stött format används kodas utdataströmmen som Jpeg som standard.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputImagesStreams | List`1 | Listan med bildströmmar som ska slås samman. |
| outputImageFormat | ImageFormat | Bildutdataformat för den sammanslagna strömmen. |
| mergeMode | ImageMergeMode | Sammanslagningsläge. Används för PNG/JPG-format. |
| horizontal | Nullable`1 | Horisontellt förhållande för att ange canvasbredden för utdata‑bildströmmen. Används endast för PNG/JPG-format med ImageMergeMode.Center. |
| vertical | Nullable`1 | Vertikal förhållande för att ange canvashöjd för utdata bildström. Används endast för Png/Jpg-format med ImageMergeMode.Center. |

### Returvärde

Bildström kodad som utdata bildformat.

### Se även

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


