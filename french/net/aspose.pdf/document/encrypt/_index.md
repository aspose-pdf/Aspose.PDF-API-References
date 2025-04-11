---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Méthode Document. Crypte le document. Appelez ensuite Save pour obtenir la version cryptée du document
type: docs
weight: 620
url: /fr/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Crypte le document. Appelez ensuite Save pour obtenir la version cryptée du document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur. |
| ownerPassword | String | Mot de passe propriétaire. |
| privileges | DocumentPrivilege | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| cryptoAlgorithm | CryptoAlgorithm | Algorithme cryptographique, voir [`CryptoAlgorithm`](../cryptoalgorithm/) pour plus de détails. |
| usePdf20 | Boolean | Support pour la révision 6 (Extension 8). |

### Exemples

L'exemple suivant montre comment crypter des fichiers PDF avec [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

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

### Voir aussi

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Crypte le document. Appelez ensuite Save pour obtenir la version cryptée du document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur. |
| ownerPassword | String | Mot de passe propriétaire. |
| permissions | Permissions | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| cryptoAlgorithm | CryptoAlgorithm | Algorithme cryptographique, voir [`CryptoAlgorithm`](../cryptoalgorithm/) pour plus de détails. |

### Voir aussi

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Crypte le document. Appelez ensuite Save pour obtenir la version cryptée du document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe utilisateur. |
| ownerPassword | String | Mot de passe propriétaire. |
| permissions | Permissions | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| cryptoAlgorithm | CryptoAlgorithm | Algorithme cryptographique, voir [`CryptoAlgorithm`](../cryptoalgorithm/) pour plus de détails. |
| usePdf20 | Boolean | Support pour la révision 6 (Extension 8). |

### Voir aussi

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)