---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileSecurity. تشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتحدد صلاحيات الوصول إلى المستندات. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. لا ترمي استثناءً إذا فشل المعالجة
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## طريقة PdfFileSecurity.TryEncryptFile

تشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتحدد صلاحيات الوصول إلى المستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. لا ترمي استثناءً إذا فشل المعالجة.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| privilege | DocumentPrivilege | تعيين الصلاحية. |
| keySize | KeySize | KeySize.x40 لتشفير 40 بت، KeySize.x128 لتشفير 128 بت و KeySize.x256 لتشفير 256 بت. |

### قيمة الإرجاع

صحيح للنجاح، أو خطأ.

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