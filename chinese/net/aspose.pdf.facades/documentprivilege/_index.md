---
title: DocumentPrivilege
second_title: Aspose.PDF for .NET API 参考
description: 表示访问 Pdf 文件的权限参考PdfFileSecurity./pdffilesecurity. 使用该类的方法有4种 1.直接使用预定义的权限 2.基于预定义的权限更改一些特定的权限 3.基于预定义的权限更改一些特定的Adobe Professional权限组合 4.混合way2和way3.
type: docs
weight: 2240
url: /zh/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

表示访问 Pdf 文件的权限。参考[`PdfFileSecurity`](../pdffilesecurity). 使用该类的方法有4种： 1.直接使用预定义的权限。 2.基于预定义的权限，更改一些特定的权限。 3.基于预定义的权限，更改一些特定的Adobe Professional权限组合。 4.混合way2和way3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | 全部允许。 |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | 允许汇编文件。 |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | 允许复制文件。 |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | 允许降级打印。 |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | 允许在文件中填写表格。 |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | 全部禁止。 |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | 允许修改文件的注释。 |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | 允许修改文件。 |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | 允许打印文件。 |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | 只允许在屏幕上阅读。 |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | 设置是否允许组装的权限。 true 为允许，false 为禁止。 |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | 设置是否允许复制的权限。 true 为允许，false 为禁止。 |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | 设置是否允许降级打印的权限。 true 为允许，false 为禁止。 |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | 设置是否允许填写表格的权限。 true 为允许，false 为禁止。 |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | 设置是否允许修改注释的权限。 true 为允许，false 为禁止。 |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | 设置是否允许修改内容的权限。 true 为允许，false 为禁止。 |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | 设置是否允许打印的权限。 true 为允许，false 为禁止。 |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | 设置是否允许屏幕阅读器的权限。 true 为允许，false 为禁止。 |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | 设置文档权限的更改级别。正如 Adobe Professional 的允许更改设置一样。 0：无。 1：插入、删除和旋转页面。 2：填写表单字段并签署现有签名字段。 3：评论、填写表单字段和签署现有签名字段。 4：除提取页面外的任何字段。 |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | 设置文档权限的复制级别。就像 Adobe Professional 的权限设置一样。 0：无。 1：为视障者启用屏幕阅读器设备的文本访问。 2：启用文本、图像和其他内容的复制。 |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | 设置文档权限的打印级别。就像 Adobe Professional 的允许打印设置一样。 0：无。 1：低分辨率 (150 dpi)。 2：高分辨率。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | 比较两个[`DocumentPrivilege`](../documentprivilege)对象.  要与之比较的对象。 一个有符号整数，指示此实例和值的相对值。小于零此实例小于值。 零这个实例等于值。大于零此实例大于值。 |

### 例子

```csharp
[C#]	
//方式1：直接使用预定义的权限。
DocumentPrivilege privilege = DocumentPrivilege.Print;

//方式2：基于预定义的权限，改变一些特定的权限。
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//方式3：基于预定义的权限，改变一些特定的Adobe Professional权限组合。
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4：混合way2和way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'方式一：直接使用预定义的权限。
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2：基于预定义的权限，改变一些特定的权限。
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3：基于预定义的权限和更改某些特定的 Adobe Professional 权限组合。
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4：混合way2和way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### 也可以看看

* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->