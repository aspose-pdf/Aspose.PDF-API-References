---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 对于这种类型的属性，您可以分配从自定义方法创建的委托，该方法实现了从 PDF 创建的 SVG 中提取的图像的外部保存处理，并且在将 PDF 转换为 HTML 时必须作为外部资源保存。在这种情况下，可以在该自定义代码中进行处理（例如自制保存到流或磁盘），并且该自定义代码必须返回路径（或任何其他不带引号的字符串），该路径随后将被纳入生成的 SVG 中，而不是原本假定的图像资源路径。在这种情况下，必须在提供的方法的代码中进行保存图像的所有必要操作，因为转换器代码中的结果保存将不被使用。如果出于某种原因，必须由转换器的代码本身而不是自定义代码处理此或那文件，请在自定义代码中设置 'imageSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志。这向转换器发出信号，表明处理该资源的所有必要步骤必须在转换器本身中完成，就好像没有任何外部自定义代码一样。表示有关已保存图像的信息，可以在自定义代码中使用，必须返回表示将放入 SVG 的图像 URL 的字符串。
type: docs
weight: 10240
url: /zh/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy 委托

对于这种类型的属性，您可以分配从自定义方法创建的委托，该方法实现了从 PDF 创建的 SVG 中提取的图像的外部保存处理，并且在将 PDF 转换为 HTML 时必须作为外部资源保存。在这种情况下，可以在该自定义代码中进行处理（例如自制保存到流或磁盘），并且该自定义代码必须返回路径（或任何其他不带引号的字符串），该路径随后将被纳入生成的 SVG 中，而不是原本假定的图像资源路径。在这种情况下，必须在提供的方法的代码中进行保存图像的所有必要操作，因为转换器代码中的结果保存将不被使用。如果出于某种原因，必须由转换器的代码本身而不是自定义代码处理此或那文件，请在自定义代码中设置 'imageSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志。这向转换器发出信号，表明处理该资源的所有必要步骤必须在转换器本身中完成，就好像没有任何外部自定义代码一样。表示有关已保存图像的信息，可以在自定义代码中使用，必须返回表示将放入 SVG 的图像 URL 的字符串。

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### 另请参阅

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)