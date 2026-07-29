---
title: "枚举 HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes 枚举。转换后的 PDF 可以包含栅格图像（.png、.jpeg 等）。此枚举定义了在 PDF 转换为 HTML 过程中如何处理栅格图像的方法。"
type: docs
weight: 5850
url: /zh/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

转换后的 PDF 可以包含栅格图像（.png、*.jpeg 等）。此枚举定义了在 PDF 转换为 HTML 过程中如何处理栅格图像的方法。

```csharp
public enum RasterImagesSavingModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | 对于每个不同的栅格文件，将生成包装 SVG 图像，并将栅格图像以 Base64 编码字符串嵌入该 SVG 图像中。 |
| AsExternalPngFilesReferencedViaSvg | `1` | 不同的栅格图像将分别保存为 PNG 文件，但会通过包装 SVG 图像进行引用，即为每个栅格图像生成一个 PNG 文件和一个 SVG 文件，每个 SVG 中包含指向相应 PNG 文件的链接。 |
| AsEmbeddedPartsOfPngPageBackground | `2` | 将为每个结果页生成一个大的 PNG 背景文件。栅格图像将嵌入该文件并作为图像的区域进行渲染。不会为每个图像生成外部 PNG 文件，每页仅会在转换结果文件集中出现一个 PNG 文件。 |
| DontSave | `3` | 对于固定布局，不保存图像 |

### 另请参见

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


