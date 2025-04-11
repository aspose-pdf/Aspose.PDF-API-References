---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptionsResourceSavingInfo 类。该类表示与在将 PDF 转换为其他格式（例如 HTML）时发生的外部资源文件保存相关的数据集。
type: docs
weight: 9940
url: /zh/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo 类

该类表示与在将 PDF 转换为其他格式（例如 HTML）时发生的外部资源文件保存相关的数据集。

```csharp
public class ResourceSavingInfo
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | 由转换器设置。假定的文件名，从转换器传递到自定义方法的代码中。可以在自定义代码中使用，以决定如何处理或将该文件保存到何处。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | 由转换器设置。表示保存文件的二进制内容。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 如果由于某种原因提议的文件应该不是通过自定义代码处理，而是通过转换器的代码以标准方式处理，则此标志必须在自定义代码中设置为“true”。因此，将其设置为 true 意味着自定义代码没有处理引用的文件，转换器必须自行处理（在保存到某处和在引用文件中命名这两个方面）。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | 由转换器设置。假定的文件名，从转换器传递到自定义方法的代码中。可以在自定义代码中使用，以决定如何处理或将该文件保存到何处。 |

### 另请参阅

* 类 [SaveOptions](../saveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)