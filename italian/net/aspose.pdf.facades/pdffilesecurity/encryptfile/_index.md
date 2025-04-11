---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity method. Encrypts Pdf file with userpassword and ownerpassword and sets the documents privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Cripta il file Pdf con userpassword e ownerpassword e imposta i privilegi di accesso del documento. La password dell'utente e la password del proprietario possono essere null o vuote. La password del proprietario sarà sostituita con una stringa casuale se la password del proprietario in input è null o vuota. Genera un'eccezione se il processo fallisce.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | Password dell'utente. |
| ownerPassword | String | Password del proprietario. |
| privilege | DocumentPrivilege | Imposta il privilegio. |
| keySize | KeySize | KeySize.x40 per crittografia a 40 bit, KeySize.x128 per crittografia a 128 bit e KeySize.x256 per crittografia a 256 bit. |

### Return Value

True per successo.

## Examples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Cripta il file Pdf con userpassword e ownerpassword e imposta i privilegi di accesso del documento. La password dell'utente e la password del proprietario possono essere null o vuote. La password del proprietario sarà sostituita con una stringa casuale se la password del proprietario in input è null o vuota. Ci sono 6 possibili combinazioni di valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono non validi e verrà sollevata un'eccezione se il kit incontra questa combinazione. Genera un'eccezione se il processo fallisce.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | Password dell'utente. |
| ownerPassword | String | Password del proprietario. |
| privilege | DocumentPrivilege | Imposta il privilegio. |
| keySize | KeySize | KeySize.x40 per crittografia a 40 bit, KeySize.x128 per crittografia a 128 bit e KeySize.x256 per crittografia a 256 bit. |
| cipher | Algorithm | Algorithm.AES per crittografare utilizzando l'algoritmo AES o Algorithm.RC4 per crittografia RC4. |

### Return Value

True per successo.

## Examples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)