---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 您可以将此属性分配给从自定义方法创建的委托，该方法实现了从 PDF 中提取的外部资源（字体或图像）的处理，并且在将 PDF 转换为 HTML 时必须作为外部资源保存。在这种情况下，可以在该自定义代码中进行处理（例如保存到流或磁盘），并且该自定义代码必须返回路径（或任何其他不带引号的字符串），该路径随后将被纳入生成的 HTML 中，而不是原本应指向该图像资源的路径。在这种情况下，所有保存图像所需的操作必须在提供的方法的代码中进行，因为转换器的代码中将不使用结果的保存。如果出于某种原因，必须由转换器的代码本身而不是自定义代码处理此或那文件，请在自定义代码中设置 'resourceSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志。这向转换器发出信号，表示处理该资源所需的所有步骤必须在转换器本身中完成，就好像没有任何外部自定义代码一样。
type: docs
weight: 5730
url: /zh/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy 委托

您可以将此属性分配给从自定义方法创建的委托，该方法实现了从 PDF 中提取的外部资源（字体或图像）的处理，并且在将 PDF 转换为 HTML 时必须作为外部资源保存。在这种情况下，可以在该自定义代码中进行处理（例如保存到流或磁盘），并且该自定义代码必须返回路径（或任何其他不带引号的字符串），该路径随后将被纳入生成的 HTML 中，而不是原本应指向该图像资源的路径。在这种情况下，所有保存图像所需的操作必须在提供的方法的代码中进行，因为转换器的代码中将不使用结果的保存。如果出于某种原因，必须由转换器的代码本身而不是自定义代码处理此或那文件，请在自定义代码中设置 'resourceSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志。这向转换器发出信号，表示处理该资源所需的所有步骤必须在转换器本身中完成，就好像没有任何外部自定义代码一样。

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | 表示用于保存资源的数据集 |

### 返回值

必须返回将用于生成 HTML 的已保存资源的 URL

### 另请参阅

* 类 [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* 类 [HtmlSaveOptions](../htmlsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)