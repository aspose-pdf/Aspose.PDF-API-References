---
title: "DocumentPrivilege Class"
linktitle: "DocumentPrivilege"
articleTitle: "DocumentPrivilege"
second_title: "Aspose.PDF for .NET"
description: "Represents the privileges for accessing Pdf file. Refer to. There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined..."
type: docs
weight: 120
url: "/net/aspose.pdf.facades/documentprivilege/"
keywords: "DocumentPrivilege, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## DocumentPrivilege class

Represents the privileges for accessing Pdf file. Refer to[`PdfFileSecurity`](../../aspose.pdf.facades/pdffilesecurity/).
 There are 4 ways using this class:
 1.Using predefined privilege directly.
 2.Based on a predefined privilege and change some specifical permissions.
 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
 4.Mixes the way2 and way3.

```csharp
public sealed class DocumentPrivilege
```

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
 Dim privilege As DocumentPrivilege = DocumentPrivilege.Print 
 
 'Way2: Based on a predefined privilege and change some specifical permissions.
 Dim privilege As DocumentPrivilege = DocumentPrivilege.AllowAll 
 privilege.AllowPrint = False
 privilege.AllowModifyContents = False
 
 'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
 Dim privilege As DocumentPrivilege = DocumentPrivilege.ForbidAll 
 privilege.ChangeAllowLevel = 1
 privilege.PrintAllowLevel = 2
 
 'Way4: Mixes the way2 and way3
 Dim privilege As DocumentPrivilege = DocumentPrivilege.ForbidAll 
 privilege.ChangeAllowLevel = 1
 privilege.AllowPrint = True
```

## Properties

| Name | Description |
| --- | --- |
| [AllowAll](./allowall/) { get; } | All allowed. |
| [AllowAssembly](./allowassembly/) { get; set; } | Sets the permission which allow assembly or not. |
| [AllowCopy](./allowcopy/) { get; set; } | Sets the permission which allow copy or not. |
| [AllowDegradedPrinting](./allowdegradedprinting/) { get; set; } | Sets the permission which allow degraded printing or not. |
| [AllowFillIn](./allowfillin/) { get; set; } | Sets the permission which allow fill in forms or not. |
| [AllowModifyAnnotations](./allowmodifyannotations/) { get; set; } | Sets the permission which allow modify annotations or not. |
| [AllowModifyContents](./allowmodifycontents/) { get; set; } | Sets the permission which allow modify contents or not. |
| [AllowPrint](./allowprint/) { get; set; } | Sets the permission which allow print or not. |
| [AllowScreenReaders](./allowscreenreaders/) { get; set; } | Sets the permission which allow screen readers or not. |
| [Assembly](./assembly/) { get; } | Allows assemblying file. |
| [ChangeAllowLevel](./changeallowlevel/) { get; set; } | Gets and sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. |
| [Copy](./copy/) { get; } | Allows copying file. |
| [CopyAllowLevel](./copyallowlevel/) { get; set; } | Gets and sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. |
| [DegradedPrinting](./degradedprinting/) { get; } | Allows degraded printing. |
| [FillIn](./fillin/) { get; } | Allows filling forms in file. |
| [ForbidAll](./forbidall/) { get; } | All Forbidded. |
| [ModifyAnnotations](./modifyannotations/) { get; } | Allows modifying annotations of file. |
| [ModifyContents](./modifycontents/) { get; } | Allows modifying file. |
| [Print](./print/) { get; } | Allows printing file. |
| [PrintAllowLevel](./printallowlevel/) { get; set; } | Gets and sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. |
| [ScreenReaders](./screenreaders/) { get; } | Allows to reader on screen only. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](./compareto/)(*object*) | Compares two [`DocumentPrivilege`](../../aspose.pdf.facades/documentprivilege/) objects. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

