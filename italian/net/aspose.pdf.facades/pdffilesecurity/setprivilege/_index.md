---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSecurity. Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password del proprietario sarà aggiunta da una stringa casuale. Genera un'eccezione se il processo fallisce
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password del proprietario sarà aggiunta da una stringa casuale. Genera un'eccezione se il processo fallisce.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| privilege | DocumentPrivilege | Imposta il privilegio. |

### Valore di Ritorno

True per successo.

## Esempi

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Vedi Anche

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Imposta la sicurezza del file Pdf con password originale. Genera un'eccezione se il processo fallisce.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente originale. |
| ownerPassword | String | Password proprietario originale. |
| privilege | DocumentPrivilege | Imposta il privilegio. |

### Valore di Ritorno

True per successo.

## Esempi

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Vedi Anche

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)