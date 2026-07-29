---
title: "PdfFileSecurity.SetPrivilege"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSecurity. تعيين أمان ملف Pdf باستخدام كلمات مرور المستخدم/المالك فارغة. سيتم إضافة كلمة مرور المالك بسلسلة عشوائية. يطرح استثناءً إذا فشلت العملية"
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

يضبط أمان ملف Pdf باستخدام كلمات مرور المستخدم/المالك فارغة. سيتم إضافة كلمة مرور المالك بسلسلة عشوائية. يرمي استثناءً إذا فشلت العملية.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| امتياز | DocumentPrivilege | تعيين الامتياز. |

### قيمة الإرجاع

صحيح للنجاح.

## أمثلة

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

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

يضبط أمان ملف Pdf باستخدام كلمة المرور الأصلية. يرمي استثناءً إذا فشلت العملية.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم الأصلية. |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| امتياز | DocumentPrivilege | تعيين الامتياز. |

### قيمة الإرجاع

صحيح للنجاح.

## أمثلة

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

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


