---
title: "PdfFileSecurity.TryDecryptFile"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSecurity. تقوم بفك تشفير مستند Pdf مشفر باستخدام كلمة مرور المالك. إذا لم يحتوي المستند على كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. لا تُلقي استثناءً إذا فشلت العملية"
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile method

يفك تشفير مستند Pdf مشفر باستخدام كلمة مرور المالك. إذا لم يكن للمستند كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. لا يُطلق استثناءً إذا فشلت العملية.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك. |

### قيمة الإرجاع

صحيح للنجاح، أو خطأ.

## أمثلة

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### انظر أيضًا

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


