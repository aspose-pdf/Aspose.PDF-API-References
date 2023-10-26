---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Document method. Encrypts the document. Call then Save to get encrypted version of the document
type: docs
weight: 590
url: /net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Encrypts the document. Call then Save to get encrypted version of the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privileges | DocumentPrivilege | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |
| usePdf20 | Boolean | Support for revision 6 (Extension 8). |

### Examples

The following example shows how to encrypt PDF files with [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

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
* class [Document](../../document/)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Encrypts the document. Call then Save to get encrypted version of the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |

### See Also

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../../document/)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Encrypts the document. Call then Save to get encrypted version of the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |
| usePdf20 | Boolean | Support for revision 6 (Extension 8). |

### See Also

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../../document/)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


