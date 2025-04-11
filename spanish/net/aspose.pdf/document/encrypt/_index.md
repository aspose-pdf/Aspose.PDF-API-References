---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Método de documento. Encripta el documento. Luego llama a Guardar para obtener la versión encriptada del documento
type: docs
weight: 620
url: /es/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Encripta el documento. Luego llama a Guardar para obtener la versión encriptada del documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña del usuario. |
| ownerPassword | String | Contraseña del propietario. |
| privileges | DocumentPrivilege | Permisos del documento, consulta [`Permissions`](../permissions/) para más detalles. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo criptográfico, consulta [`CryptoAlgorithm`](../cryptoalgorithm/) para más detalles. |
| usePdf20 | Boolean | Soporte para la revisión 6 (Extensión 8). |

### Ejemplos

El siguiente ejemplo muestra cómo encriptar archivos PDF con [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

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

### Ver También

* clase [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Encripta el documento. Luego llama a Guardar para obtener la versión encriptada del documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña del usuario. |
| ownerPassword | String | Contraseña del propietario. |
| permissions | Permissions | Permisos del documento, consulta [`Permissions`](../permissions/) para más detalles. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo criptográfico, consulta [`CryptoAlgorithm`](../cryptoalgorithm/) para más detalles. |

### Ver También

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Encripta el documento. Luego llama a Guardar para obtener la versión encriptada del documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña del usuario. |
| ownerPassword | String | Contraseña del propietario. |
| permissions | Permissions | Permisos del documento, consulta [`Permissions`](../permissions/) para más detalles. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo criptográfico, consulta [`CryptoAlgorithm`](../cryptoalgorithm/) para más detalles. |
| usePdf20 | Boolean | Soporte para la revisión 6 (Extensión 8). |

### Ver También

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* clase [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)