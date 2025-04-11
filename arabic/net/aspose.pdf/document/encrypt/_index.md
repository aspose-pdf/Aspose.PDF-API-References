---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: طريقة الوثيقة. تشفر الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المشفرة من الوثيقة
type: docs
weight: 620
url: /ar/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

تشفر الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المشفرة من الوثيقة.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| privileges | DocumentPrivilege | أذونات الوثيقة، انظر [`Permissions`](../permissions/) لمزيد من التفاصيل. |
| cryptoAlgorithm | CryptoAlgorithm | الخوارزمية التشفيرية، انظر [`CryptoAlgorithm`](../cryptoalgorithm/) لمزيد من التفاصيل. |
| usePdf20 | Boolean | دعم للإصدار 6 (الامتداد 8). |

### Examples

المثال التالي يوضح كيفية تشفير ملفات PDF باستخدام [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

```csharp
[C#]

	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document document = new Document(pdfFilePath))
	{
	// Encrypt PDF
	document.Encrypt("YOUR_USER_PASSWORD", "YOUR_OWNER_PASSWORD", DocumentPrivilege.AllowAll, CryptoAlgorithm.RC4x128, true);

	// Save updated PDF
	document.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
    
	' Open document
    Using document As Document = New Document(pdfFilePath)
        ' Encrypt PDF
        document.Encrypt("YOUR_USER_PASSWORD", "YOUR_OWNER_PASSWORD", DocumentPrivilege.AllowAll, CryptoAlgorithm.RC4x128, True)
        ' Save updated PDF
        document.Save(pdfFilePath)
    End Using
```

### See Also

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

تشفر الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المشفرة من الوثيقة.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| permissions | Permissions | أذونات الوثيقة، انظر [`Permissions`](../permissions/) لمزيد من التفاصيل. |
| cryptoAlgorithm | CryptoAlgorithm | الخوارزمية التشفيرية، انظر [`CryptoAlgorithm`](../cryptoalgorithm/) لمزيد من التفاصيل. |

### See Also

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

تشفر الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المشفرة من الوثيقة.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| permissions | Permissions | أذونات الوثيقة، انظر [`Permissions`](../permissions/) لمزيد من التفاصيل. |
| cryptoAlgorithm | CryptoAlgorithm | الخوارزمية التشفيرية، انظر [`CryptoAlgorithm`](../cryptoalgorithm/) لمزيد من التفاصيل. |
| usePdf20 | Boolean | دعم للإصدار 6 (الامتداد 8). |

### See Also

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)