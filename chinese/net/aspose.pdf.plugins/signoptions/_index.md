---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.SignOptions class. 表示签名插件的签名选项
type: docs
weight: 9250
url: /zh/net/aspose.pdf.plugins/signoptions/
---
## SignOptions class

表示[`Signature`](../signature/)插件的签名选项。

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | 使用默认选项初始化`SignOptions`对象的新实例。 |
| [SignOptions](signoptions/#constructor_1)(string, string) | 使用默认选项初始化`SignOptions`对象的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 操作完成后关闭输入流。 |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 操作完成后关闭输出流。 |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | 签名的联系人。 |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | 返回OrganizerOptions插件数据集合。 |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | 签名的位置。 |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | 现有签名字段的名称。为null以创建新字段。 |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 获取用于保存操作结果的添加目标的集合。 |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | 签名所在的页码。 |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | 签名的原因。 |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | 签名的矩形区域。 |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | 签名的可见性。 |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | 将新的数据源添加到PdfOrganizer插件数据集合。 |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | 将新的数据源添加到PdfOrganizer插件数据集合。 |

### See Also

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)