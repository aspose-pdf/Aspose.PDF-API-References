---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSecurity. Imposta la sicurezza del file Pdf con la password originale. Non genera un'eccezione se il processo fallisce
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## Metodo PdfFileSecurity.TrySetPrivilege

Imposta la sicurezza del file Pdf con la password originale. Non genera un'eccezione se il processo fallisce.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password originale dell'utente. |
| ownerPassword | String | Password originale del proprietario. |
| privilege | DocumentPrivilege | Imposta il privilegio. |

### Valore di Ritorno

True per successo, o false.

## Esempi

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Vedi Anche

* classe [DocumentPrivilege](../../documentprivilege/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)