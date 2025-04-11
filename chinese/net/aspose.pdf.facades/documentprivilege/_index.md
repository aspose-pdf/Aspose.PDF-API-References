---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.DocumentPrivilege 类。表示访问 Pdf 文件的权限。参考 PdfFileSecurity。使用此类有 4 种方式：1. 直接使用预定义权限。2. 基于预定义权限并更改一些特定权限。3. 基于预定义权限并更改一些特定的 Adobe Professional 权限组合。4. 混合方式 2 和方式 3。
type: docs
weight: 4230
url: /zh/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

表示访问 Pdf 文件的权限。参考 [`PdfFileSecurity`](../pdffilesecurity/)。使用此类有 4 种方式：1. 直接使用预定义权限。2. 基于预定义权限并更改一些特定权限。3. 基于预定义权限并更改一些特定的 Adobe Professional 权限组合。4. 混合方式 2 和方式 3。

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Properties

| Name | Description |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | 所有允许。 |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | 允许组装文件。 |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | 允许复制文件。 |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | 允许降级打印。 |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | 允许填写文件中的表单。 |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | 所有禁止。 |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | 允许修改文件的注释。 |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | 允许修改文件。 |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | 允许打印文件。 |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | 仅允许在屏幕上阅读。 |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | 设置允许或不允许组装的权限。 true 允许，false 禁止。 |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | 设置允许或不允许复制的权限。 true 允许，false 禁止。 |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | 设置允许或不允许降级打印的权限。 true 允许，false 禁止。 |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | 设置允许或不允许填写表单的权限。 true 允许，false 禁止。 |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | 设置允许或不允许修改注释的权限。 true 允许，false 禁止。 |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | 设置允许或不允许修改内容的权限。 true 允许，false 禁止。 |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | 设置允许或不允许打印的权限。 true 允许，false 禁止。 |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | 设置允许或不允许屏幕阅读器的权限。 true 允许，false 禁止。 |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | 获取和设置文档权限的更改级别。就像 Adobe Professional 的允许更改设置。 0: 无。 1: 插入、删除和旋转页面。 2: 填写表单字段和签署现有签名字段。 3: 注释、填写表单字段和签署现有签名字段。 4: 除提取页面外的任何操作。 |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | 获取和设置文档权限的复制级别。就像 Adobe Professional 的权限设置。 0: 无。 1: 为视力障碍者启用屏幕阅读设备的文本访问。 2: 启用文本、图像和其他内容的复制。 |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | 获取和设置文档权限的打印级别。就像 Adobe Professional 的允许打印设置。 0: 无。 1: 低分辨率 (150 dpi)。 2: 高分辨率。 |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | 比较两个 `DocumentPrivilege` 对象。要比较的对象。一个表示此实例和值的相对值的整数。小于零时，此实例小于值。零时，此实例等于值。大于零时，此实例大于值。 |

## Examples

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)