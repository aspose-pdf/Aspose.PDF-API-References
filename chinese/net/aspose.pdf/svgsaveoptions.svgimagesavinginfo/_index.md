---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo 类。该类表示与在 PDF 转换为 HTML 过程中外部资源图像文件保存相关的数据集。
type: docs
weight: 10260
url: /zh/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo 类

该类表示与在 PDF 转换为 HTML 过程中外部资源图像文件的保存相关的数据集。

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | 由转换器设置。假定的文件名，从转换器传递到自定义方法的代码中。可以在自定义代码中使用，以决定如何处理或将该文件保存到何处。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | 由转换器设置。表示保存文件的二进制内容。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 如果由于某种原因提议的文件应通过转换器的代码而不是自定义代码进行处理，则此标志必须设置为“true”。因此，将其设置为 true 意味着自定义代码未处理引用的文件，转换器必须自行处理（在保存到某处和在引用文件中命名的两个方面）。 |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | 表示在 HTML 中引用的保存图像的类型。由转换器设置，可以在自定义代码中使用，以决定应该做什么。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | 由转换器设置。假定的文件名，从转换器传递到自定义方法的代码中。可以在自定义代码中使用，以决定如何处理或将该文件保存到何处。 |

### 另请参阅

* 类 [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* 类 [SvgSaveOptions](../svgsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)