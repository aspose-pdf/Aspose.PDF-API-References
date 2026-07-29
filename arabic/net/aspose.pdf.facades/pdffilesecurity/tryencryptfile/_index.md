---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSecurity. تشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتحدد صلاحيات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. لا تُلقي استثناءً إذا فشلت العملية"
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

يشفّر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويضبط صلاحيات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. لا يُطلق استثناءً إذا فشلت العملية.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| امتياز | DocumentPrivilege | تعيين الامتياز. |
| keySize | KeySize | KeySize.x40 للتشفير 40 بت، KeySize.x128 للتشفير 128 بت وKeySize.x256 للتشفير 256 بت. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


