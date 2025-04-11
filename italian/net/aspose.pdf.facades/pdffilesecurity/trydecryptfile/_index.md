---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSecurity. Decripta un documento Pdf crittografato con la password del proprietario. Se il documento non ha la password del proprietario, è consentito utilizzare la password dell'utente. Non genera un'eccezione se il processo fallisce.
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## Metodo PdfFileSecurity.TryDecryptFile

Decripta un documento Pdf crittografato con la password del proprietario. Se il documento non ha la password del proprietario, è consentito utilizzare la password dell'utente. Non genera un'eccezione se il processo fallisce.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password del proprietario. |

### Valore di ritorno

Vero per successo, o falso.

## Esempi

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### Vedi anche

* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)