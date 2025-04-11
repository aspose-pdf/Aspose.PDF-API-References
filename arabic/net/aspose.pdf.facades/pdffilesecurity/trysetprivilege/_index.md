---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileSecurity. تعيين أمان ملف Pdf باستخدام كلمة المرور الأصلية. لا ترمي استثناءً إذا فشل العملية
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## طريقة PdfFileSecurity.TrySetPrivilege

تعيين أمان ملف Pdf باستخدام كلمة المرور الأصلية. لا ترمي استثناءً إذا فشل العملية.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | سلسلة | كلمة المرور الأصلية للمستخدم. |
| ownerPassword | سلسلة | كلمة المرور الأصلية للمالك. |
| privilege | DocumentPrivilege | تعيين الامتياز. |

### قيمة الإرجاع

صحيح للنجاح، أو خطأ.

## أمثلة

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)