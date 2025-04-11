---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Método do documento. Criptografa o documento. Chame então Save para obter a versão criptografada do documento
type: docs
weight: 620
url: /pt/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Criptografa o documento. Chame então Save para obter a versão criptografada do documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | Senha do usuário. |
| ownerPassword | String | Senha do proprietário. |
| privileges | DocumentPrivilege | Permissões do documento, veja [`Permissions`](../permissions/) para detalhes. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo criptográfico, veja [`CryptoAlgorithm`](../cryptoalgorithm/) para detalhes. |
| usePdf20 | Boolean | Suporte para a revisão 6 (Extensão 8). |

### Exemplos

O exemplo a seguir mostra como criptografar arquivos PDF com [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

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

### Veja Também

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Criptografa o documento. Chame então Save para obter a versão criptografada do documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | Senha do usuário. |
| ownerPassword | String | Senha do proprietário. |
| permissions | Permissions | Permissões do documento, veja [`Permissions`](../permissions/) para detalhes. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo criptográfico, veja [`CryptoAlgorithm`](../cryptoalgorithm/) para detalhes. |

### Veja Também

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Criptografa o documento. Chame então Save para obter a versão criptografada do documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | Senha do usuário. |
| ownerPassword | String | Senha do proprietário. |
| permissions | Permissions | Permissões do documento, veja [`Permissions`](../permissions/) para detalhes. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo criptográfico, veja [`CryptoAlgorithm`](../cryptoalgorithm/) para detalhes. |
| usePdf20 | Boolean | Suporte para a revisão 6 (Extensão 8). |

### Veja Também

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)