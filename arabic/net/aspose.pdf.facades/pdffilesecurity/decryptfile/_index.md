---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileSecurity. تقوم بفك تشفير مستند Pdf مشفر بواسطة كلمة مرور المالك. إذا لم يكن لدى المستند كلمة مرور للمالك، يُسمح باستخدام كلمة مرور المستخدم. ترمي استثناءً إذا فشل العملية
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## طريقة PdfFileSecurity.DecryptFile

تقوم بفك تشفير مستند Pdf مشفر بواسطة كلمة مرور المالك. إذا لم يكن لدى المستند كلمة مرور للمالك، يُسمح باستخدام كلمة مرور المستخدم. ترمي استثناءً إذا فشل العملية.

```csharp
public bool DecryptFile(string ownerPassword)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك. |

### قيمة الإرجاع

True للنجاح.

## أمثلة

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### انظر أيضًا

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)