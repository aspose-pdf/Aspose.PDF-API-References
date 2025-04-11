---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter 方法。将图像流列表合并为一个图像流。支持 Png/jpg/tiff 输出格式，如果使用不支持的格式输出流，默认编码为 Jpeg。
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages 方法

将图像流列表合并为一个图像流。支持 Png/jpg/tiff 输出格式，如果使用不支持的格式输出流，默认编码为 Jpeg。

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputImagesStreams | List`1 | 要合并的图像流列表。 |
| outputImageFormat | ImageFormat | 合并流的图像输出格式。 |
| mergeMode | ImageMergeMode | 合并模式。用于 Png/Jpg 格式。 |
| horizontal | Nullable`1 | 设置输出图像流画布宽度的水平比例。仅在使用 ImageMergeMode.Center 的 Png/Jpg 格式时使用。 |
| vertical | Nullable`1 | 设置输出图像流画布高度的垂直比例。仅在使用 ImageMergeMode.Center 的 Png/Jpg 格式时使用。 |

### 返回值

编码为输出图像格式的图像流。

### 另请参阅

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)