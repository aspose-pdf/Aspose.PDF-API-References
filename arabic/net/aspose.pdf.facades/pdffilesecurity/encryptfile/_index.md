---
title: "PdfFileSecurity.EncryptFile"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSecurity. تشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتحدد امتيازات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. يطرح استثناءً إذا فشلت العملية."
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

يشفّر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويضبط صلاحيات الوصول للمستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. يرمي استثناءً إذا فشلت العملية.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| امتياز | DocumentPrivilege | تعيين الامتياز. |
| keySize | KeySize | KeySize.x40 للتشفير 40 بت، KeySize.x128 للتشفير 128 بت وKeySize.x256 للتشفير 256 بت. |

### قيمة الإرجاع

صحيح للنجاح.

## أمثلة

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

يشفّر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويضبط صلاحيات الوصول للمستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. هناك 6 تركيبات محتملة لقيم KeySize و Algorithm. ومع ذلك، التركيبة (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع استثناء مناسب إذا واجهت الأداة هذه التركيبة. يرمي استثناءً إذا فشلت العملية.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| امتياز | DocumentPrivilege | تعيين الامتياز. |
| keySize | KeySize | KeySize.x40 للتشفير 40 بت، KeySize.x128 للتشفير 128 بت وKeySize.x256 للتشفير 256 بت. |
| شفرة | خوارزمية | Algorithm.AES للتشفير باستخدام خوارزمية AES أو Algorithm.RC4 لتشفير RC4. |

### قيمة الإرجاع

صحيح للنجاح.

## أمثلة

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


