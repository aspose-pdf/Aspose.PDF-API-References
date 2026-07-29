---
title: "类 SignOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Plugins.SignOptions 类。表示 Signature 插件的签名选项。"
type: docs
weight: 9400
url: /zh/net/aspose.pdf.plugins/signoptions/
---
## SignOptions class

表示 [`Signature`](../signature/) 插件的签名选项。

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | 使用默认选项初始化 `SignOptions` 对象的新实例。 |
| [SignOptions](signoptions/#constructor_1)(string, string) | 使用默认选项初始化 `SignOptions` 对象的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 在操作完成后关闭输入流。 |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 在操作完成后关闭输出流。 |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | 签名的联系人。 |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | 返回 OrganizerOptions 插件的数据集合。 |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | 签名的位置。 |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | 现有签名字段的名称。为 Null 时将创建新字段。 |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 获取已添加目标的集合，用于保存操作结果。 |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | 签名所在的页码。 |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | 签名的原因。 |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | 签名的矩形区域。 |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | 签名的可见性。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | 向 PdfOrganizer 插件的数据集合添加新数据源。 |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | 向 PdfOrganizer 插件的数据集合添加新数据源。 |

### 另请参见

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


