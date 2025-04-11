---
title: PdfFileSecurity.TryChangePassword
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSecurity. Cambia la password utente e la password proprietario mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario sarà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se il processo fallisce.
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Cambia la password utente e la password proprietario mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario sarà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se il processo fallisce.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password proprietario originale. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password proprietario. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Vedi Anche

* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Cambia la password utente e la password proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario sarà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se il processo fallisce.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password proprietario originale. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password proprietario. |
| privilege | DocumentPrivilege | Ripristina la sicurezza. |
| keySize | KeySize | KeySize.x40 per crittografia a 40 bit, KeySize.x128 per crittografia a 128 bit e KeySize.x256 per crittografia a 256 bit. |

### Valore di ritorno

True per successo, o false.

## Esempi

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Vedi Anche

* classe [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Cambia la password utente e la password proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario sarà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Ci sono 6 possibili combinazioni di valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e verrà sollevata un'eccezione se il kit incontra questa combinazione. Non genera un'eccezione se il processo fallisce.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
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

True per successo, o false.

## Esempi

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Vedi Anche

* classe [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)