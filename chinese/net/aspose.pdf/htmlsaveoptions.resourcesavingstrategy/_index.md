---
title: HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API 参考
description: 到此属性您可以分配从自定义方法创建的委托该方法实现从 PDF 中提取的外部资源字体或图像 的处理 在将 PDF 转换为 HTML 期间必须保存为外部资源 在这种情况下处理就像保存在流或磁盘中 可以在该自定义代码中完成并且该自定义代码必须返回路径或任何其他不带引号的字符串 之后将合并到生成的 HTML 中而不是该图像资源的原始假定路径 在这种情况下保存图像的所有必要操作都必须在提供的方法的代码中进行 因为将不使用转换器代码中的结果保存 如果出于某种原因必须由转换器的代码本身而不是在自定义代码中处理这个或那个文件 请在resourceSavingInfo参数的变量的自定义代码标志CustomProcessingCancelled中设置 它向转换器发出信号表明所有必要的步骤该资源 的处理必须在转换器本身中完成就好像没有任何外部自定义代码一样
type: docs
weight: 3600
url: /zh/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

到此属性您可以分配从自定义方法创建的委托，该方法实现从 PDF 中提取的外部资源（字体或图像） 的处理 ，在将 PDF 转换为 HTML 期间必须保存为外部资源。 在这种情况下处理（就像保存在流或磁盘中） 可以在该自定义代码中完成，并且该自定义代码必须返回路径（或任何其他不带引号的字符串） 之后将合并到生成的 HTML 中，而不是该图像资源的原始假定路径。 在这种情况下，保存图像的所有必要操作都必须在提供的方法的代码中进行 ，因为将不使用转换器代码中的结果保存。 如果出于某种原因必须由转换器的代码本身而不是在自定义代码中处理这个或那个文件， 请在'resourceSavingInfo'参数的变量的自定义代码标志'CustomProcessingCancelled'中设置 它向转换器发出信号，表明所有必要的步骤该资源 的处理必须在转换器本身中完成，就好像没有任何外部自定义代码一样。

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | 表示用于节省资源的数据集 |

### 返回值

必须返回将在生成 HTML 期间使用的已保存资源的 URL

### 也可以看看

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo)
* class [HtmlSaveOptions](../htmlsaveoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->