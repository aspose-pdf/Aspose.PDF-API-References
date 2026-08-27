---
title: "类 PdfFileInfo"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfFileInfo 类。表示用于访问 PDF 文档元信息的类。"
type: docs
weight: 4640
url: /zh/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

表示用于访问 PDF 文档元信息的类。

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | 使用默认值初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfFileInfo` 对象。 |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo/#constructor_6)(string, string) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo/#constructor_4)(Stream, string, ICustomSecurityHandler) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| [PdfFileInfo](pdffileinfo/#constructor_7)(string, string, ICustomSecurityHandler) | 初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | 获取或设置 PDF 文档的作者信息。 |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | 获取或设置 PDF 文档的创建日期信息。 |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | 获取或设置 PDF 文档的创建者信息。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | 如果当前输入文件是包含 PDF 文件集合的 “Portfolio” 文件，则返回 true。 |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | 如果需要密码来修改权限或文档安全属性，则返回 true。请注意，仅当在 `PdfFileInfo` 构造函数中提供了有效密码时，才能读取此属性。如果 PasswordType 为 Inaccessible（表示提供了无效密码），读取此属性将因 [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/) 而失败。 |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | 如果需要密码才能打开受密码保护的 pdf 文档，则返回 true。 |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | 获取或设置 PDF 文档的自定义信息。 |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | 检查 PDF 文档是否已加密。 |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | 检查源输入是否为有效的 PDF 文件。 |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | 获取或设置 PDF 文档的 Keywords 信息。 |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | 获取或设置 PDF 文档的 ModDate 日期信息。 |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | 获取文档的页数。 |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | 返回用于创建 PdfFileInfo 实例的密码类型。请参阅 [`PasswordType`](./passwordtype/) 中的可能取值。请注意，pdf 文档可以使用用户（或打开）密码和所有者（或权限、编辑）密码两者之一打开。 |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | 获取 PDF 文档的 Producer 信息。 |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | 获取或设置 PDF 文档的 Subject 信息。 |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | 获取或设置 PDF 文档的 Title 信息。 |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | 通过使用 [`IsPdfFile`](./ispdffile/) 属性来使用严格的验证规则。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化 facade。 |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | 清除 PDF 文档的所有元信息。 |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | 对实例进行反初始化。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | 获取 PDF 文档的特权设置。 |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | 获取具有属性名称的 PDF 文档的自定义信息。如果没有匹配该名称的属性，则返回空字符串。 |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | 获取指定页面的高度。 |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | 获取指定页面的旋转角度。 |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | 获取指定页面的宽度。 |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | 获取指定页面显示区域的水平偏移。 |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | 获取指定页面显示区域的垂直偏移。 |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | 获取 PDF 文档的版本信息。 |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | 将 PDF 文档保存到指定的文件中。 |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | 将 PDF 文档保存到指定的文件中。 |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | 将更新后的 PDF 文档保存到指定文件。 |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | 通过设置文件信息显式更改指定属性，其他属性保持不变。 |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | 设置 PDF 文档的自定义信息。 |

### 另请参见

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


