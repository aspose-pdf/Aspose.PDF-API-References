---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.SubmitFormAction class. 描述提交表单操作的类
type: docs
weight: 2640
url: /zh/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

描述提交表单操作的类。

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Constructors

| Name | Description |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | 初始化 SubmitFormAction 对象。 |

## Properties

| Name | Description |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | 获取或设置提交操作的标志 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | 顺序中的下一个操作。 |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | 目标 URL。 |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | 获取 ECMAScript 操作的字符串。 |

## Fields

| Name | Description |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | 如果设置，任何提交的字段值表示的日期将转换为标准格式。 |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | 如果设置，提交的 FDF 的 F 条目将是包含表示提交 FDF 的 PDF 文件的嵌入文件流的文件规范。 |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | 如果设置，提交的 FDF 将排除 F 条目。 |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | 如果设置，它将仅包括 T 条目与当前用户名称匹配的标记注释。 |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | 如果清除，Fields 数组指定要包含在提交中的字段。 |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | 如果设置，字段名称和值将以 HTML 表单格式提交。 |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | 如果设置，字段名称和值将使用 HTTP GET 请求提交。 |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | 如果设置，提交的 FDF 文件将包括底层 PDF 文档中的所有标记注释。 |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | 如果设置，提交的 FDF 文件将包括所有增量更新的内容。 |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | 如果设置，Fields 数组和 Include/Exclude 标志指定的所有字段将被提交。 |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | 如果设置，导致提交表单操作的鼠标点击的坐标将作为表单数据的一部分传输。 |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | 如果设置，文档将作为 PDF 提交，使用 MIME 内容类型 application/pdf。 |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | 如果设置，字段名称和值将作为 XFDF 提交。 |

### See Also

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)