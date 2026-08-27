---
title: "Class SubmitFormAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.SubmitFormAction 类。描述提交表单操作的类。"
type: docs
weight: 2740
url: /zh/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

描述提交表单操作的类。

```csharp
public sealed class SubmitFormAction : PdfAction
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | 初始化 SubmitFormAction 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | 获取或设置提交操作的标志。 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | 序列中的下一个操作。 |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | 目标 URL。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | 获取 ECMAScript 操作的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | 如果设置，则任何表示日期的提交字段值都将转换为标准格式。 |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | 如果设置，则提交的 FDF 的 F 条目应为文件规范，其中包含一个嵌入的文件流，表示提交 FDF 的 PDF 文件。 |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | 如果设置，则提交的 FDF 应排除 F 条目。 |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | 如果设置，则仅应包含那些 T 条目匹配当前用户名称的标记注释。 |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | 如果未设置，则 Fields 数组指定要在提交中包含的字段。 |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | 如果设置，则字段名称和值应以 HTML 表单格式提交。 |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | 如果设置，则字段名称和值应使用 HTTP GET 请求提交。 |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | 如果设置，则提交的 FDF 文件应包含底层 PDF 文档中的所有标记注释。 |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | 如果设置，则提交的 FDF 文件应包含所有增量更新的内容。 |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | 如果设置，则应提交由 Fields 数组和 Include/Exclude 标志指定的所有字段。 |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | 如果设置，则导致 submit-form 操作的鼠标点击坐标应作为表单数据的一部分传输。 |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | 如果设置，则文档应以 PDF 形式提交，使用 MIME 内容类型 application/pdf。 |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | 如果设置，则字段名称和值应以 XFDF 形式提交。 |

### 另请参见

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


