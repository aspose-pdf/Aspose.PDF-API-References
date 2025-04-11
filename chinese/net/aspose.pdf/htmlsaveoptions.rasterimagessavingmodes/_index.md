---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes 枚举。转换后的 PDF 可以包含光栅图像.png .jpeg 等。此枚举定义了在将 PDF 转换为 HTML 时如何处理光栅图像的方法
type: docs
weight: 5720
url: /zh/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes 枚举

转换后的 PDF 可以包含光栅图像（.png，*.jpeg 等）。此枚举定义了在将 PDF 转换为 HTML 时如何处理光栅图像的方法

```csharp
public enum RasterImagesSavingModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | 对于每个不同的光栅文件，将生成包装的 SVG 图像，光栅图像将作为 Base64 编码的字符串嵌入到该 SVG 图像中 |
| AsExternalPngFilesReferencedViaSvg | `1` | 不同的光栅图像将作为 PNG 文件分开存放，但将通过包装的 SVG 图像进行引用，即将为每个光栅图像生成一个 PNG 文件和一个 SVG，每个这样的 SVG 将包含指向相关 PNG 文件的链接 |
| AsEmbeddedPartsOfPngPageBackground | `2` | 将为每个结果页面生成一个大的 PNG 背景文件。光栅图像将嵌入到该文件中，并作为该图像的区域进行渲染。不会为每个图像生成外部 PNG 文件，转换结果文件集中每页只会存在一个 PNG 文件。 |
| DontSave | `3` | 不保存固定布局的图像 |

### 另请参阅

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)