---
title: PdfFileSecurity.ChangePassword
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSecurity. Cambia la password utente e la password proprietario mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password proprietario sarà sostituita con una stringa casuale se la nuova password proprietario è nulla o vuota. Genera un'eccezione se il processo fallisce.
type: docs
weight: 40
url: /it/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

Cambia la password utente e la password proprietario mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password proprietario sarà sostituita con una stringa casuale se la nuova password proprietario è nulla o vuota. Genera un'eccezione se il processo fallisce.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password proprietario originale. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password proprietario. |

### Valore di ritorno

True per successo.

## Esempi

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### Vedi anche

* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

Cambia la password utente e la password proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password proprietario sarà sostituita con una stringa casuale se la nuova password proprietario è nulla o vuota. Genera un'eccezione se il processo fallisce.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password proprietario originale. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password proprietario. |
| privilege | DocumentPrivilege | Ripristina la sicurezza. |
| keySize | KeySize | KeySize.x40 per crittografia a 40 bit, KeySize.x128 per crittografia a 128 bit e KeySize.x256 per crittografia a 256 bit. |

### Valore di ritorno

True per successo.

## Esempi

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Vedi anche

* classe [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

Cambia la password utente e la password proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password proprietario sarà sostituita con una stringa casuale se la nuova password proprietario è nulla o vuota. Ci sono 6 possibili combinazioni di valori KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono non validi e verrà sollevata un'eccezione se il kit incontra questa combinazione. Genera un'eccezione se il processo fallisce.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password proprietario originale. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password proprietario. |
| privilege | DocumentPrivilege | Ripristina la sicurezza. |
| keySize | KeySize | KeySize.x40 per crittografia a 40 bit, KeySize.x128 per crittografia a 128 bit e KeySize.x256 per crittografia a 256 bit. |
| cipher | Algorithm | Algorithm.AES per crittografare utilizzando l'algoritmo AES o Algorithm.RC4 per crittografia RC4. |

### Valore di ritorno

True per successo.

## Esempi

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Vedi anche

* classe [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)