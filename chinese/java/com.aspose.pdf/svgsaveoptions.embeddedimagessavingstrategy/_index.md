---
title: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
linktitle: "SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "对于此类型的 To 属性，您可以分配由自定义方法创建的委托，该方法实现对从 PDF 创建的 SVG 中提取的图像的外部保存处理。"
type: docs
weight: 4730
url: /zh/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

要为此类属性分配委托，可使用自定义方法创建的委托，该方法实现对从 PDF 创建的 SVG 中提取的图像的外部保存处理，并在 PDF 转 HTML 的转换过程中将其保存为外部资源。在这种情况下，处理（例如自行保存到流或磁盘）可以在该自定义代码中完成，并且该自定义代码必须返回路径（或任何不带引号的字符串），该路径随后会被合并到生成的 SVG 中，替代原本应指向该图像资源的路径。在这种情况下，所有保存图像的必要操作必须在提供的方法代码中完成，因为转换器代码中的结果保存将不再使用。如果出于某种原因必须由转换器的代码本身（而不是自定义代码）处理此文件或那个文件，请在自定义代码中设置 'CustomProcessingCancelled' 标志，针对 'imageSavingInfo' 参数的变量。它向转换器指示，所有对该资源的必要处理步骤应由转换器自行完成，就像没有任何外部自定义代码一样。

## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |

### invoke {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
