---
title: "PdfConverter.MergeImages"
linktitle: "MergeImages"
articleTitle: "MergeImages"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfConverter method. Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format outp..."
type: docs
weight: 530
url: "/net/aspose.pdf.facades/pdfconverter/mergeimages/"
product_version: "26.9.0"
---
## MergeImages(List<Stream>, [ImageFormat](../../../aspose.pdf.drawing/imageformat/), [ImageMergeMode](../../../aspose.pdf.facades/imagemergemode/), Nullable<int>, Nullable<int>) {#mergeimages}

Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format output stream encoded as Jpeg by default.

```csharp
public Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, ImageMergeMode mergeMode, Nullable<int> horizontal, Nullable<int> vertical)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputImagesStreams | List<Stream> | The list of image streams to merge. |
| outputImageFormat | ImageFormat | Image output format for merged stream. |
| mergeMode | ImageMergeMode | Merge mode. Used for Png/Jpg formats. |
| horizontal | Nullable<int> | Horizontal ratio to set canvas width for output image stream. Used for Png/Jpg formats with ImageMergeMode.Center only. |
| vertical | Nullable<int> | Vertical ratio to set canvas height for output image stream. Used for Png/Jpg formats with ImageMergeMode.Center only. |

### Return Value

[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Image stream encoded as output image format.

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

