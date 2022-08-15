---
title: TryChangePassword
second_title: Aspose.PDF per .NET API Reference
description: Modifica la password utente e la password del proprietario in base alla password del proprietario mantiene le impostazioni di sicurezza originali. La nuova password utente e la nuova password del proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita Non genera uneccezione se il processo non riesce. con una stringa casuale se la nuova password del proprietario è nulla o vuota.
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Modifica la password utente e la password del proprietario in base alla password del proprietario, mantiene le impostazioni di sicurezza originali. La nuova password utente e la nuova password del proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita Non genera un'eccezione se il processo non riesce. con una stringa casuale se la nuova password del proprietario è nulla o vuota.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password del proprietario originale. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password del proprietario. |

### Valore di ritorno

Vero per il successo, o falso.

### Esempi

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //Il TestPath potrebbe essere riassegnato.
 string outFile = "D:\\output.pdf";	//Il TestPath potrebbe essere riassegnato.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Guarda anche

* class [PdfFileSecurity](../../pdffilesecurity)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesecurity)
* assemblea [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Modifica la password utente e la password in base alla password del proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è nulla o vuota. Non genera un'eccezione se il processo non riesce.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password originale del proprietario. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password del proprietario. |
| privilege | DocumentPrivilege | Ripristina sicurezza. |
| keySize | KeySize | KeySize.x40 per la crittografia a 40 bit, KeySize.x128 per la crittografia a 128 bit e KeySize.x256 per la crittografia a 256 bit. |

### Valore di ritorno

Vero per il successo o falso.

### Esempi

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //Il TestPath potrebbe essere riassegnato.
string outFile = "D:\\output.pdf";	//Il TestPath potrebbe essere riassegnato.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Guarda anche

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesecurity)
* assemblea [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Modifica la password utente e la password in base alla password del proprietario, consente di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere nulle o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è nulla o vuota. Esistono 6 possibili combinazioni di valori KeySize e Algoritmo. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) non sono validi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Non genera un'eccezione se il processo non riesce.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password originale del proprietario. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password del proprietario. |
| privilege | DocumentPrivilege | Ripristina sicurezza. |
| keySize | KeySize | KeySize.x40 per la crittografia a 40 bit, KeySize.x128 per la crittografia a 128 bit e KeySize.x256 per la crittografia a 256 bit. |
| cipher | Algorithm | Algoritmo.AES per crittografare utilizzando l'algoritmo AES o Algoritmo.RC4 per crittografare RC4. |

### Valore di ritorno

Vero per il successo o falso.

### Esempi

```csharp
[C#]
string inFile = "D:\\input.pdf"; //Il TestPath potrebbe essere riassegnato.
string outFile = "D:\\output.pdf";	//Il TestPath potrebbe essere riassegnato.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Guarda anche

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilesecurity)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
