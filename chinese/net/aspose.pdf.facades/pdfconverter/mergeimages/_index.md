---
title: "PdfConverter.MergeImages"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfConverter 方法。将图像流列表合并为一个图像流。支持 Png、jpg、tiff 输出格式；如果使用不受支持的格式，则默认将输出流编码为 JPEG。"
type: docs
weight: 180
url: /zh/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

将图像流列表合并为一个图像流。支持 Png/jpg/tiff 输出格式，如果使用不受支持的格式，输出流默认编码为 Jpeg。

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputImagesStreams | List`1 | 要合并的图像流列表。 |
| outputImageFormat | ImageFormat | 合并流的图像输出格式。 |
| mergeMode | ImageMergeMode | 合并模式。用于 Png/Jpg 格式。 |
| 水平 | Nullable`1 | 水平比例，用于设置输出图像流的画布宽度。仅在使用 ImageMergeMode.Center 的 Png/Jpg 格式中使用。 |
| 垂直 | Nullable`1 | 垂直比例，用于设置输出图像流的画布高度。仅在使用 ImageMergeMode.Center 的 Png/Jpg 格式中使用。 |

### 返回值

图像流已编码为输出图像格式。

### 另请参见

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


