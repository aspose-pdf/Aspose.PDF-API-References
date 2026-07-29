---
title: "委托 HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "对于此属性，您可以分配由自定义方法创建的委托，该方法实现对从 PDF 中提取的外部资源 Font 或 Image 的处理，并且在 PDF 转换为 HTML 的过程中必须将其保存为外部资源。在这种情况下，诸如在流或磁盘中保存的处理可以在自定义代码中完成，并且该自定义代码必须返回路径或其他不带引号的字符串，该字符串随后会被嵌入生成的 HTML 中，取代原本应指向该图像资源的路径。此时，所有保存图像的必要操作必须在提供的方法代码中完成，因为转换器代码中的保存结果将不会被使用。如果由于某种原因必须由转换器自身的代码而非自定义代码来处理此文件或该文件，请在自定义代码中设置 `CustomProcessingCancelled` 标志（resourceSavingInfo 参数的变量）。它向转换器指示，所有对该资源的必要处理步骤必须在转换器内部完成，就像没有任何外部自定义代码一样。"
type: docs
weight: 5860
url: /zh/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

对于此属性，您可以分配由自定义方法创建的委托，该方法实现对从 PDF 中提取的外部资源（Font 或 Image）的处理，并且在 PDF 转换为 HTML 的过程中必须将其保存为外部资源。在这种情况下，诸如在流或磁盘中保存的处理可以在自定义代码中完成，并且该自定义代码必须返回路径（或其他不带引号的字符串），该字符串随后会被嵌入生成的 HTML 中，取代原本应指向该图像资源的路径。此时，所有保存图像的必要操作必须在提供的方法代码中完成，因为转换器代码中的保存结果将不会被使用。如果由于某种原因必须由转换器自身的代码而非自定义代码来处理此文件或该文件，请在自定义代码中设置 ‘CustomProcessingCancelled’ 标志（‘resourceSavingInfo’ 参数的变量）。它向转换器指示，所有对该资源的必要处理步骤必须在转换器内部完成，就像没有任何外部自定义代码一样。

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | 表示用于保存资源的数据集合 |

### 返回值

必须返回已保存资源的 URL，该 URL 将在生成 HTML 时使用

### 另请参见

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


