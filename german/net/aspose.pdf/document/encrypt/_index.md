---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmethode. Verschlüsselt das Dokument. Rufen Sie dann Speichern auf, um die verschlüsselte Version des Dokuments zu erhalten
type: docs
weight: 620
url: /de/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Verschlüsselt das Dokument. Rufen Sie dann Speichern auf, um die verschlüsselte Version des Dokuments zu erhalten.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Benutzerpasswort. |
| ownerPassword | String | Eigentümerpasswort. |
| privileges | DocumentPrivilege | Dokumentberechtigungen, siehe [`Permissions`](../permissions/) für Details. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografischer Algorithmus, siehe [`CryptoAlgorithm`](../cryptoalgorithm/) für Details. |
| usePdf20 | Boolean | Unterstützung für Revision 6 (Erweiterung 8). |

### Beispiele

Das folgende Beispiel zeigt, wie man PDF-Dateien mit [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege) verschlüsselt.

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

### Siehe auch

* Klasse [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Verschlüsselt das Dokument. Rufen Sie dann Speichern auf, um die verschlüsselte Version des Dokuments zu erhalten.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Benutzerpasswort. |
| ownerPassword | String | Eigentümerpasswort. |
| permissions | Permissions | Dokumentberechtigungen, siehe [`Permissions`](../permissions/) für Details. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografischer Algorithmus, siehe [`CryptoAlgorithm`](../cryptoalgorithm/) für Details. |

### Siehe auch

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Verschlüsselt das Dokument. Rufen Sie dann Speichern auf, um die verschlüsselte Version des Dokuments zu erhalten.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Benutzerpasswort. |
| ownerPassword | String | Eigentümerpasswort. |
| permissions | Permissions | Dokumentberechtigungen, siehe [`Permissions`](../permissions/) für Details. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografischer Algorithmus, siehe [`CryptoAlgorithm`](../cryptoalgorithm/) für Details. |
| usePdf20 | Boolean | Unterstützung für Revision 6 (Erweiterung 8). |

### Siehe auch

* Enum [Permissions](../../permissions/)
* Enum [CryptoAlgorithm](../../cryptoalgorithm/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)