---
title: PdfFileInfo
second_title: Aspose.PDF for .NET API 参考
description: 表示访问PDF文档元信息的类
type: docs
weight: 2530
url: /zh/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

表示访问PDF文档元信息的类。

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PdfFileInfo](pdffileinfo#constructor)() | 使用默认值初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo#constructor_1)(Document) | 在*document*的基础上初始化新的[`PdfFileInfo`](../pdffileinfo)对象。 |
| [PdfFileInfo](pdffileinfo#constructor_2)(Stream) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo#constructor_4)(string) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo#constructor_3)(Stream, string) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo#constructor_5)(string, string) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author) { get; set; } | 获取或设置PDF文档的作者信息。 |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate) { get; set; } | 获取或设置PDF文档的CreationDate信息。 |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator) { get; set; } | 获取或设置 PDF 文档的 Creator 信息。 |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | 获取正在处理的文档外观。 |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection) { get; } | 如果当前输入文件是包含 PDF 文件集合的“组合”文件，则返回 true。 |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword) { get; } | 如果需要密码来修改权限或文档安全属性，则返回 true。 请注意，只有在[`PdfFileInfo`](../pdffileinfo)构造函数中提供了有效密码时，才能读取此属性。 如果 PasswordType 无法访问（意味着提供了无效密码），读取此属性将失败，并显示[`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception)。 |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword) { get; } | 如果需要密码才能打开受密码保护的 pdf 文档，则返回 true。 |
| [Header](../../aspose.pdf.facades/pdffileinfo/header) { get; set; } | 获取或设置PDF文档的自定义信息。 |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted) { get; } | 检查 PDF 文档是否加密。 |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile) { get; } | 检查源输入是否是有效的 PDF 文件。 |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords) { get; set; } | 获取或设置PDF文档的关键词信息。 |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate) { get; set; } | 获取或设置PDF文档的ModDate日期信息。 |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages) { get; } | 获取文档页数。 |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype) { get; } | 返回用于创建 PdfFileInfo 实例的密码类型。查看[`PasswordType`](./passwordtype)中的可能值。 请注意，可以使用用户（或打开）密码和所有者（或权限，编辑）密码打开 pdf 文档。 |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer) { get; } | 获取PDF文档的Producer信息。 |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject) { get; set; } | 获取或设置PDF文档的主题信息。 |
| [Title](../../aspose.pdf.facades/pdffileinfo/title) { get; set; } | 获取或设置PDF文档的标题信息。 |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation) { get; set; } | 通过使用[`IsPdfFile`](./ispdffile)属性使用严格的验证规则。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf#bindpdf)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | 初始化外观。 |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo)() | 清除 PDF 文档的所有元信息。 |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close)() | 取消初始化实例。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | 配置外观。 |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege)() | 获取 PDF 文档权限设置。 |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo)(string) | 获取带有属性名称的PDF文档的自定义信息。如果没有与名称匹配的属性，它将返回一个空白字符串。 |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight)(int) | 获取指定页面的高度。 |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation)(int) | 获取指定页面的旋转。 |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth)(int) | 获取指定页面的宽度。 |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset)(int) | 获取指定页面显示区域的水平偏移量。 |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset)(int) | 获取指定页面显示区域的垂直偏移量。 |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion)() | 获取PDF文档的版本信息。 |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save)(Stream) | 将 PDF 文档保存到指定文件。 |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save_1)(string) | 将 PDF 文档保存到指定文件。 |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo#savenewinfo_1)(string) | 将更新的 PDF 文档保存到指定文件中。 |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp)(string) | 更改通过设置文件信息明确指定的属性，其他属性保留。 |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo)(string, string) | 设置PDF文档的自定义信息。 |

### 也可以看看

* class [SaveableFacade](../saveablefacade)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
