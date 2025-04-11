---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Metodo Document. Cripta il documento. Chiama poi Salva per ottenere la versione criptata del documento
type: docs
weight: 620
url: /it/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Cripta il documento. Chiama poi Salva per ottenere la versione criptata del documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password proprietario. |
| privileges | DocumentPrivilege | Permessi del documento, vedere [`Permissions`](../permissions/) per dettagli. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo crittografico, vedere [`CryptoAlgorithm`](../cryptoalgorithm/) per dettagli. |
| usePdf20 | Boolean | Supporto per la revisione 6 (Estensione 8). |

### Esempi

Il seguente esempio mostra come criptare file PDF con [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

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

### Vedi Anche

* classe [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Cripta il documento. Chiama poi Salva per ottenere la versione criptata del documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password proprietario. |
| permissions | Permissions | Permessi del documento, vedere [`Permissions`](../permissions/) per dettagli. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo crittografico, vedere [`CryptoAlgorithm`](../cryptoalgorithm/) per dettagli. |

### Vedi Anche

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Cripta il documento. Chiama poi Salva per ottenere la versione criptata del documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password proprietario. |
| permissions | Permissions | Permessi del documento, vedere [`Permissions`](../permissions/) per dettagli. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo crittografico, vedere [`CryptoAlgorithm`](../cryptoalgorithm/) per dettagli. |
| usePdf20 | Boolean | Supporto per la revisione 6 (Estensione 8). |

### Vedi Anche

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)