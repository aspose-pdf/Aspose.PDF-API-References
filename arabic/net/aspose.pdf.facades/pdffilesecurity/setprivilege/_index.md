---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileSecurity. تعيين أمان ملف Pdf مع كلمات مرور مستخدم/مالك فارغة. سيتم إضافة كلمة مرور المالك بواسطة سلسلة عشوائية. يتم طرح استثناء إذا فشل المعالجة
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

تعيين أمان ملف Pdf مع كلمات مرور مستخدم/مالك فارغة. سيتم إضافة كلمة مرور المالك بواسطة سلسلة عشوائية. يتم طرح استثناء إذا فشل المعالجة.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| privilege | DocumentPrivilege | تعيين الامتياز. |

### Return Value

صحيح للنجاح.

## Examples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

تعيين أمان ملف Pdf مع كلمة المرور الأصلية. يتم طرح استثناء إذا فشل المعالجة.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم الأصلية. |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| privilege | DocumentPrivilege | تعيين الامتياز. |

### Return Value

صحيح للنجاح.

## Examples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)