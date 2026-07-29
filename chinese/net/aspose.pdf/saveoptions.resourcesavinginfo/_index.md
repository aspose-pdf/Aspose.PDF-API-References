---
title: "类 SaveOptions.ResourceSavingInfo"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.SaveOptionsResourceSavingInfo 类。此类表示与在将 PDF 转换为其他格式（例如 HTML）期间外部资源文件保存相关的一组数据。"
type: docs
weight: 10090
url: /zh/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

此类表示与在将 PDF 转换为其他格式（例如 HTML）期间外部资源文件保存相关的一组数据。

```csharp
public class ResourceSavingInfo
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | 由转换器设置。假定的文件名从转换器传递到自定义方法的代码，可在自定义代码中使用，以决定如何处理或将文件保存在哪里。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | 由转换器设置。表示已保存文件的二进制内容。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 如果出于某些原因建议的文件应由转换器的代码而非自定义代码进行处理，则必须在自定义代码中将此标志设置为 \"true\"。因此，将此设置为 true 表示自定义代码未处理引用的文件，转换器必须自行处理它（包括保存位置和在引用文件中的命名）。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | 由转换器设置。假定的文件名从转换器传递到自定义方法的代码，可在自定义代码中使用，以决定如何处理或将文件保存在哪里。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


