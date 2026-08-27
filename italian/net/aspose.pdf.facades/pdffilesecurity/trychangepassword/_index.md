---
title: "PdfFileSecurity.TryChangePassword"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileSecurity. Modifica la user password e la owner password mantenendo le impostazioni di sicurezza originali tramite la owner password. La nuova user password e la nuova owner password possono essere null o vuote. La owner password sarà sostituita con una stringa casuale se la nuova owner password è null o vuota. Non genera un'eccezione se il processo fallisce."
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Modifica la password utente e la password proprietario tramite la password proprietario, mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se l'operazione fallisce.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password originale del proprietario. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password del proprietario. |

### Valore di ritorno

True per indicare il successo, o false.

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

### Vedi anche

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Modifica la password utente e la password tramite la password proprietario, consentendo di ripristinare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se l'operazione fallisce.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password proprietario originale. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password del proprietario. |
| privilegio | DocumentPrivilege | Reimposta sicurezza. |
| keySize | KeySize | KeySize.x40 per la crittografia a 40 bit, KeySize.x128 per la crittografia a 128 bit e KeySize.x256 per la crittografia a 256 bit. |

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

### Vedi anche

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Modifica la password utente e la password del proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è null o vuota. Esistono 6 combinazioni possibili di valori KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e verrà sollevata l'eccezione corrispondente se il kit incontra questa combinazione. Non genera un'eccezione se il processo fallisce.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password proprietario originale. |
| newUserPassword | String | Nuova password utente. |
| newOwnerPassword | String | Nuova password del proprietario. |
| privilegio | DocumentPrivilege | Reimposta sicurezza. |
| keySize | KeySize | KeySize.x40 per la crittografia a 40 bit, KeySize.x128 per la crittografia a 128 bit e KeySize.x256 per la crittografia a 256 bit. |
| cipher | Algorithm | Algorithm.AES per cifrare usando l'algoritmo AES o Algorithm.RC4 per la crittografia RC4. |

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

### Vedi anche

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


