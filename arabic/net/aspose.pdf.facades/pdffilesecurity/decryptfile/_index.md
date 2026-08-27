---
title: "PdfFileSecurity.DecryptFile"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSecurity. تقوم بفك تشفير مستند Pdf مشفر باستخدام كلمة مرور المالك. إذا لم يحتوي المستند على كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. تُلقي استثناءً إذا فشلت العملية"
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

يفك تشفير مستند Pdf مشفر باستخدام كلمة مرور المالك. إذا لم يكن للمستند كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. يرمي استثناءً إذا فشلت العملية.

```csharp
public bool DecryptFile(string ownerPassword)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك. |

### قيمة الإرجاع

صحيح للنجاح.

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


