---
title: SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: 用于 Java API 参考的 Aspose.PDF
description: 对于这种类型的属性您可以分配从自定义方法创建的委托，该方法实现了从 PDF 创建的 SVG 中提取的图像的外部保存处理，并且在将 PDF 转换为 HTML 期间必须将其保存为外部资源。
type: docs
weight: 12
url: /zh/java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

对于这种类型的属性您可以分配从自定义方法创建的委托，该方法实现了从 PDF 创建的 SVG 中提取的图像的外部保存处理，并且在将 PDF 转换为 HTML 期间必须将其保存为外部资源。在这种情况下，处理（如自制保存到流或磁盘上）可以在该自定义代码中完成，并且该自定义代码必须返回路径（或任何其他不带引号的字符串），该路径随后将被合并到生成的 SVG 中，而不是原来假设的该图像资源的路径。在这种情况下，必须在提供的方法代码中执行保存图像的所有必要操作，因为在转换器代码中保存结果将不会被使用。如果由于某种原因必须由转换器代码本身而不是自定义代码来处理这个或那个文件，请在“imageSavingInfo”参数变量的自定义代码标志“CustomProcessingCancelled”中设置它向转换器发出信号，表明所有必要的处理步骤该资源必须在转换器本身中完成，就好像没有任何外部自定义代码一样。
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |
### invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo) {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
```
public abstract String invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageSavingInfo | [SvgImageSavingInfo](../../com.aspose.pdf/svgimagesavinginfo) |  |

**退货：**
java.lang.字符串