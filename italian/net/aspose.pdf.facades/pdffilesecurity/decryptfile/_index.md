---
title: "PdfFileSecurity.DecryptFile"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileSecurity. Decripta un documento Pdf crittografato con la password del proprietario. Se il documento non ha una password del proprietario, è consentito utilizzare la password utente. Lancia un'eccezione se l'operazione fallisce"
type: docs
weight: 60
url: /it/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

Decifra un documento Pdf crittografato tramite la password proprietario. Se il documento non ha una password proprietario, è consentito utilizzare la password utente. Genera un'eccezione se l'operazione fallisce.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ownerPassword | String | Password del proprietario. |

### Valore di ritorno

True per il successo.

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

### Vedi anche

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


