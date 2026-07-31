---
title: "PdfFileSecurity.EncryptFile"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileSecurity. Cifra il file Pdf con userpassword e ownerpassword e imposta i privilegi dei documenti per l'accesso. La userpassword e la ownerpassword possono essere null o vuote. La ownerpassword sarà sostituita con una stringa casuale se la ownerpassword di input è null o vuota. Genera un'eccezione se il processo fallisce"
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Cifra un file Pdf con password utente e password proprietario e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la password proprietario in ingresso è null o vuota. Genera un'eccezione se l'operazione fallisce.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password del proprietario. |
| privilegio | DocumentPrivilege | Imposta privilegio. |
| keySize | KeySize | KeySize.x40 per la crittografia a 40 bit, KeySize.x128 per la crittografia a 128 bit e KeySize.x256 per la crittografia a 256 bit. |

### Valore di ritorno

True per il successo.

## Esempi

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

### Vedi anche

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Cifra un file Pdf con password utente e password proprietario e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la password proprietario in ingresso è null o vuota. Esistono 6 combinazioni possibili dei valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Genera un'eccezione se l'operazione fallisce.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password del proprietario. |
| privilegio | DocumentPrivilege | Imposta privilegio. |
| keySize | KeySize | KeySize.x40 per la crittografia a 40 bit, KeySize.x128 per la crittografia a 128 bit e KeySize.x256 per la crittografia a 256 bit. |
| cipher | Algorithm | Algorithm.AES per cifrare usando l'algoritmo AES o Algorithm.RC4 per la crittografia RC4. |

### Valore di ritorno

True per il successo.

## Esempi

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

### Vedi anche

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


