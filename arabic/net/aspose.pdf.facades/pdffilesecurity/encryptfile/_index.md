---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileSecurity. تشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتحدد صلاحيات الوصول إلى المستندات. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. يتم إلقاء استثناء إذا فشل العملية
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

تشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتحدد صلاحيات الوصول إلى المستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. يتم إلقاء استثناء إذا فشل العملية.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| privilege | DocumentPrivilege | تعيين الصلاحية. |
| keySize | KeySize | KeySize.x40 لتشفير 40 بت، KeySize.x128 لتشفير 128 بت و KeySize.x256 لتشفير 256 بت. |

### Return Value

True للنجاح.

## Examples

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

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

تشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتحدد صلاحيات الوصول إلى المستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. هناك 6 تركيبات ممكنة من قيم KeySize و Algorithm. ومع ذلك (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحة وسيتم رفع استثناء إذا واجهت المجموعة هذا. يتم إلقاء استثناء إذا فشل العملية.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| privilege | DocumentPrivilege | تعيين الصلاحية. |
| keySize | KeySize | KeySize.x40 لتشفير 40 بت، KeySize.x128 لتشفير 128 بت و KeySize.x256 لتشفير 256 بت. |
| cipher | Algorithm | Algorithm.AES للتشفير باستخدام خوارزمية AES أو Algorithm.RC4 لتشفير RC4. |

### Return Value

True للنجاح.

## Examples

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

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)