---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmetod. Krypterar dokumentet. Anropa sedan Spara för att få den krypterade versionen av dokumentet
type: docs
weight: 620
url: /sv/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Krypterar dokumentet. Anropa sedan Spara för att få den krypterade versionen av dokumentet.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | Sträng | Användarlösenord. |
| ownerPassword | Sträng | Ägarlösenord. |
| privileges | DocumentPrivilege | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografisk algoritm, se [`CryptoAlgorithm`](../cryptoalgorithm/) för detaljer. |
| usePdf20 | Boolean | Stöd för revision 6 (Extension 8). |

### Exempel

Följande exempel visar hur man krypterar PDF-filer med [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

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

### Se Även

* klass [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* klass [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Krypterar dokumentet. Anropa sedan Spara för att få den krypterade versionen av dokumentet.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | Sträng | Användarlösenord. |
| ownerPassword | Sträng | Ägarlösenord. |
| permissions | Permissions | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografisk algoritm, se [`CryptoAlgorithm`](../cryptoalgorithm/) för detaljer. |

### Se Även

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* klass [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Krypterar dokumentet. Anropa sedan Spara för att få den krypterade versionen av dokumentet.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | Sträng | Användarlösenord. |
| ownerPassword | Sträng | Ägarlösenord. |
| permissions | Permissions | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografisk algoritm, se [`CryptoAlgorithm`](../cryptoalgorithm/) för detaljer. |
| usePdf20 | Boolean | Stöd för revision 6 (Extension 8). |

### Se Även

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* klass [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)