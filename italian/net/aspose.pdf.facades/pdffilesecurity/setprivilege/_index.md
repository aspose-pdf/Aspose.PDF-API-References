---
title: "PdfFileSecurity.SetPrivilege"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileSecurity. Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password del proprietario verrà aggiunta con una stringa casuale. Genera un'eccezione se il processo fallisce"
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password proprietario sarà aggiunta con una stringa casuale. Genera un'eccezione se l'operazione fallisce.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| privilegio | DocumentPrivilege | Imposta privilegio. |

### Valore di ritorno

True per il successo.

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

### Vedi anche

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Imposta la sicurezza del file Pdf con la password originale. Genera un'eccezione se l'operazione fallisce.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente originale. |
| ownerPassword | String | Password proprietario originale. |
| privilegio | DocumentPrivilege | Imposta privilegio. |

### Valore di ritorno

True per il successo.

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

### Vedi anche

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


