---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF for Java API 参考"
description: "转换后的 PDF 可能包含光栅图像（.png、.jpeg 等）。此枚举定义了在 PDF 转换为 HTML 期间如何处理光栅图像的方法"
type: docs
weight: 2140
url: /zh/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

转换后的 PDF 可能包含光栅图像（.png、.jpeg 等）。此枚举定义了在 PDF 转换为 HTML 期间如何处理光栅图像的方法

## 字段

| 字段 | 描述 |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | 每个结果页将生成一个大的 PNG 背景文件。光栅图像将嵌入该文件并渲染为该图像的区域。不会为每个图像生成外部 PNG 文件，每页只会在转换结果文件集中出现一个 PNG 文件。 |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | 不同的光栅图像将分别保存为 PNG 文件，但会通过包装的 SVG 图像进行引用，即为每个光栅图像生成一个 PNG 文件和一个 SVG 文件，并且每个此类 SVG 将包含指向相应 PNG 文件的链接。 |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | 对于每个不同的光栅文件，将生成包装 SVG 图像，并将光栅图像以 Base64 编码字符串嵌入该 SVG 图像中。 |
| [DontSave](#DontSave) | 不要为固定布局保存图像 |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

每个结果页将生成一个大的 PNG 背景文件。光栅图像将嵌入该文件并渲染为该图像的区域。不会为每个图像生成外部 PNG 文件，每页只会在转换结果文件集中出现一个 PNG 文件。

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

不同的光栅图像将分别保存为 PNG 文件，但会通过包装的 SVG 图像进行引用，即为每个光栅图像生成一个 PNG 文件和一个 SVG 文件，并且每个此类 SVG 将包含指向相应 PNG 文件的链接。

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

对于每个不同的光栅文件，将生成包装 SVG 图像，并将光栅图像以 Base64 编码字符串嵌入该 SVG 图像中。

### DontSave {#DontSave}
```
public static final int DontSave
```

不要为固定布局保存图像
