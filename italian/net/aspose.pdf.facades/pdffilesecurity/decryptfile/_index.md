---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSecurity. Decripta un documento Pdf crittografato tramite la password del proprietario. Se il documento non ha una password del proprietario, è consentito utilizzare la password dell'utente. Genera un'eccezione se il processo fallisce.
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## Metodo PdfFileSecurity.DecryptFile

Decripta un documento Pdf crittografato tramite la password del proprietario. Se il documento non ha una password del proprietario, è consentito utilizzare la password dell'utente. Genera un'eccezione se il processo fallisce.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password del proprietario. |

### Valore di ritorno

True per successo.

## Esempi

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### Vedi Anche

* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)