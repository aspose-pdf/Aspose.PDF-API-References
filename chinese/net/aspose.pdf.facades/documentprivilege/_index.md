---
title: "类 DocumentPrivilege"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.DocumentPrivilege 类。表示访问 Pdf 文件的权限。请参阅PdfFileSecurity。使用此类有 4 种方式：1.直接使用预定义的权限。2.基于预定义的权限并更改某些特定权限。3.基于预定义的权限并更改某些特定的 Adobe Professional 权限组合。4.混合方式 2 和方式 3。"
type: docs
weight: 4350
url: /zh/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

表示访问 Pdf 文件的权限。请参阅[`PdfFileSecurity`](../pdffilesecurity/)。使用此类有 4 种方式：1.直接使用预定义的权限。2.基于预定义的权限并更改某些特定权限。3.基于预定义的权限并更改某些特定的 Adobe Professional 权限组合。4.混合方式 2 和方式 3。

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | 全部允许。 |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | 允许组装文件。 |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | 允许复制文件。 |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | 允许低质量打印。 |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | 允许在文件中填写表单。 |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | 全部禁止。 |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | 允许修改文件的批注。 |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | 允许修改文件。 |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | 允许打印文件。 |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | 仅允许在屏幕上阅读。 |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | 设置是否允许组装的权限。true 表示允许，false 表示禁止。 |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | 设置是否允许复制的权限。true 表示允许，false 表示禁止。 |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | 设置是否允许低质量打印的权限。true 表示允许，false 表示禁止。 |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | 设置是否允许填写表单的权限。true 表示允许，false 表示禁止。 |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | 设置是否允许修改批注的权限。true 表示允许，false 表示禁止。 |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | 设置是否允许修改内容的权限。true 表示允许，false 表示禁止。 |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | 设置是否允许打印的权限。true 表示允许，false 表示禁止。 |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | 设置是否允许屏幕阅读器的权限。true 表示允许，false 表示禁止。 |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | 获取和设置 Document 权限的更改级别。就像 Adobe Professional 的 Changes Allowed 设置。0：无。1：插入、删除和旋转页面。2：填写表单字段并签署现有签名字段。3：添加批注、填写表单字段并签署现有签名字段。4：除提取页面之外的所有操作。 |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | 获取和设置 Document 权限的复制级别。就像 Adobe Professional 的权限设置。0：无。1：为视障人士的屏幕阅读器设备启用文本访问。2：启用文本、图像和其他内容的复制。 |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | 获取和设置 Document 权限的打印级别。就像 Adobe Professional 的 Printing Allowed 设置。0：无。1：低分辨率（150 dpi）。2：高分辨率。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | 比较两个 `DocumentPrivilege` 对象。 要比较的对象。 一个有符号整数，指示此实例与 value 的相对值。 小于零表示此实例小于 value。 零表示此实例等于 value。 大于零表示此实例大于 value。 |

## 示例

```csharp
[C#]	
//方式1：直接使用预定义的权限。
DocumentPrivilege privilege = DocumentPrivilege.Print;

//方式2：基于预定义的权限并更改一些特定的权限。
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//方式3：基于预定义的权限并更改一些特定的 Adobe Professional 权限组合。
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//方式4：混合方式2和方式3。
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

### 另请参见

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


